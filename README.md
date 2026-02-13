# rentsignal-data-collector
데이터 수집·집계 파이프라인 레포지토리

## Data Collection
- Kakao Local REST API
- Legal-dong level aggregation

## Notes
- API Key stored in .env
- output CSV excluded from repo

## Raw Sources
- [법정동 CSV](raw/legal_dong.csv)
- [국토교통부_전국 버스정류장 위치정보_20251031.csv](raw/MOLIT_National_Bus_Stop_Locations_20251031.csv)
    - [서울특별시_버스정류장 위치정보.csv](output/kr_molit_bus_stops_seoul_20251031.csv)