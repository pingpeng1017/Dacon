# Dacon

### 프로젝트 개요

- 프로젝트 기간: 2023.04.18 ~ 2023.04.20
- 프로젝트 이름 및 제목: 서울시 마포구 따릉이 대여량 예측 경진대회
- 프로젝트 설명 및 소개: 서울시 마포구의 날짜별, 시간별 데이터를 바탕으로 따릉이 대여량을 예측합니다.
- 링크: https://dacon.io/competitions/open/235576/overview/description

### 데이터
1. **train.csv / test.csv**
   - **id**: 고유 id
   - **hour**: 시간
   - **temperature**: 기온
   - **precipitation**: 비가 오지 않았으면 0, 비가 오면 1
   - **windspeed**: 풍속(평균)
   - **humidity**: 습도
   - **visibility**: 시정(視程), 시계(視界) (특정 기상 상태에 따른 가시성을 의미)
   - **ozone**: 오존
   - **pm10**: 미세먼지(머리카락 굵기의 1/5에서 1/7 크기의 미세먼지)
   - **pm2.5**: 미세먼지(머리카락 굵기의 1/20에서 1/30 크기의 미세먼지)
   - **count**: 시간에 따른 따릉이 대여 수

2. **submission.csv (제출 파일 형식)**
