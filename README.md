# 서울시 부동산 및 인프라 데이터 분석
부동산 시세 평균과 전월세 비율 등 다양한 지표를 볼 수 있게 해 주택 거래 시 필요한 정보들을 확인할 수 있도록 각종 부동산 거래 통계 정보를 볼 수 있도록 하였습니다
## skills

|skill|detail|
|---|---|
| **언어** | Python,SQL |
| **데이터 웨어하우스 및 스토리지** | Snowflake, S3 |
| **대시보드** | preset |
| **ETL** | pandas |

## SW 아키텍처
<img src="https://github.com/SpaceSurfer051/seoul_realestate_info/blob/main/img/sw.png" width="1000"/>
## ERD
<img src="https://github.com/SpaceSurfer051/seoul_realestate_info/blob/main/img/project2.png" width="1000"/>

## 대시 보드 구성 및 예시 이미지
### 종합
<img src="https://github.com/SpaceSurfer051/seoul_realestate_info/blob/main/img/total_1.png" width="1000"/>
<img src="https://github.com/SpaceSurfer051/seoul_realestate_info/blob/main/img/total_2.png" width="1000"/>
<img src="https://github.com/SpaceSurfer051/seoul_realestate_info/blob/main/img/total_3.png" width="1000"/>
전체적인 데이터 테이블과 자치구/건물 용도/월을 기준으로 비교하는 종합적인 차트를 구성하였습니다.

- 서울시 구별 매매량
- 서울시 주택별 매매 선호도
- 월별 주택별 매매량
- 월별 주택별 ㎡당 평균 매매가
- 자치구별 매매 거래량 TOP 10
- 월별 자치구별 매매량
- 주택별 매매수량 테이블
- 매매 테이블
- 전세 테이블
- 월세 테이블
- 전체 월세 비율
- 매매 직거래 비중

### 매매
<img src="https://github.com/SpaceSurfer051/seoul_realestate_info/blob/main/img/sale_apt.png" width="1000"/>

- 매매 탭에서는 건물 용도(아파트, 오피스텔, 단독다가구, 연립다세대)별로 분류했습니다.
- 데이터는 2023년 1월 ~ 2024년 4월 기준으로 차트를 생성했습니다.
- 건물 용도별로 분류한 뒤, 월별 / 자치구별로 차트를 나누었습니다.
- 평균 매매가 차트의 경우, ㎡당 가격을 보여주도록 했습니다.

### 전월세
<img src="https://github.com/SpaceSurfer051/seoul_realestate_info/blob/main/img/rent_apt.png" width="1000"/>

- 전월세 탭에서는 건물 용도(아파트, 오피스텔, 단독다가구, 연립다세대)별로 분류했습니다.
- 데이터는 2024년 1월 ~ 2024년 5월 기준으로 차트를 생성했습니다.
- 건물 용도별로 분류한 뒤, 월별 / 자치구별로 차트를 나누었습니다.
- 전월세에서는 보증금과 임대료의 비교가 중요하기에 월별 / 자치구별 평균 보증금과 임대료 차트를 생성했습니다.
- 그리고 월세 비중 또한 주요하게 이용되는 수치이므로 월세 비중 차트도 생성했습니다.


### 인프라
<img src="https://github.com/SpaceSurfer051/seoul_realestate_info/blob/main/img/infra_top5.jpg" width="1000"/>
<img src="https://github.com/SpaceSurfer051/seoul_realestate_info/blob/main/img/infra_map.jpg" width="1000"/>
<img src="https://github.com/SpaceSurfer051/seoul_realestate_info/blob/main/img/infra_edu.jpg" width="1000"/>
<img src="https://github.com/SpaceSurfer051/seoul_realestate_info/blob/main/img/infra_culture.jpg" width="1000"/>
<img src="https://github.com/SpaceSurfer051/seoul_realestate_info/blob/main/img/infra_bus.png" width="1000"/>

- 인프라의 경우 크게 학군(학교, 학원), 의료(병원, 보육시설), 교통(지하철역, 버스정류장) 3종류로 나눴습니다.
    - 자치구 별로 학군, 의료, 교통의 수를 지도를 통해 전체적으로 알 수 있게 보여주었습니다












