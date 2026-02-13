# rentsignal-data-collector
서울 법정동 기준 부동산 관련 데이터 수집·집계 파이프라인 레포지토리

## Overview
> 본 레포지토리는 RentSignal 프로젝트를 위한 위치 기반 데이터 수집 및 전처리를 수행합니다.
- 수집 대상 : 
    - 카카오 Local API 기반 POI 데이터 (생활 편의시설)
    - 국토교통부 전국 버스정류장 위치 데이터 
    - 법정동 기준 집계 데이터

## Data Collection
- Kakao Local REST API
- Legal-dong level aggregation

## Notes
- API Key stored in .env
- output CSV excluded from repo

## Data Sources

### Raw
- [법정동 CSV](raw/legal_dong.csv)
- [국토교통부_전국 버스정류장 위치정보_20251031.csv](raw/MOLIT_National_Bus_Stop_Locations_20251031.csv)

### Processed Output
- [서울특별시_버스정류장 위치정보.csv](output/kr_molit_bus_stops_seoul_20251031.csv)

## Environment Setup
> 루트 디렉토리에 .env 파일을 생성하고 Kakao REST API 키를 입력합니다.
```
KAKAO_REST_API_KEY="YOUR_API_KEY_HERE"
```
