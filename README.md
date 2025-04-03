# ✈️ Domestic Flight Operation Data (Korea)

[![Python Version](https://img.shields.io/badge/Python-3.9+-blue.svg)](https://www.python.org/)
[![MySQL](https://img.shields.io/badge/Database-MySQL-lightblue.svg)](https://www.mysql.com/)

## 🔍 소개

이 프로젝트는 국내 항공 운항 데이터를 MySQL 데이터베이스에 저장하고  
향후 분석 및 시각화에 사용할 수 있도록 하는 기반 스크립트를 포함합니다.

---

## 🧩 주요 기능

- 📥 국내선 항공 운항 정보 수집 및 정리
- 🗄️ MySQL로 데이터 저장 자동화
- 📊 데이터베이스 기반 분석 환경 구성의 기초

---

## 📁 프로젝트 구조

```
📁 Domestic_flight_operation_data-master/
    └── mysql_save.py      # 국내 항공 데이터를 MySQL에 저장하는 스크립트
```

---

## 🚀 실행 방법

### 1. MySQL 설정

- MySQL이 설치되어 있고 실행 중인지 확인하세요.
- 데이터베이스 및 테이블을 먼저 생성해두세요.

### 2. 가상환경 및 패키지 설치

```bash
python -m venv venv
source venv/bin/activate
pip install mysql-connector-python
```

### 3. 실행

```bash
python mysql_save.py
```

---

## ⚙️ 환경 정보

- Python 3.9 이상
- MySQL 8.x 이상 권장
- mysql-connector-python
