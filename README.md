# Multicampus_Projects
Projects with a team from Multicampus bigdata class



## 1. Mini Project (Crawling and Visualization)

### 1) 프로젝트 주제

* 2021년 국내 베스트 펜션 숙소 시각화 (2021 Best Pension site in South Korea)

### 2) 프로젝트 개요
* 신종 코로나바이러스 감염증(코로나 19)가 발병한지 만 3년째인 2022년 초, 2021년 국민들의 여행 현황을 살펴보고자 한다.
* 국내 숙소 업계는 코로나 19로 호황기를 겪고 있는데 국내 대표 숙소 예약 어플 두 곳에 따르면 2020년, 2021년 업계 현황은 다음과 같다.
  > - 2019년 동기 대비 *국내 숙소 사전 예약 건수가 109% 증가*하고 *수도권에서 자가용으로 이동 가능*한 강원도(16.9%) 및 경기도(14.9%) 등이 여름철 인기 지역인 제주도(14.3%)와 함께 상위권을 차지, 2020년 5월 황금연휴기간에 이어 펜션(43.8%)이 이용률 1위를 기록하는 등 *타인과의 접촉 가능성이 낮은 독채형 숙소에 대한 선호도가 지속*되고 있다. (출처: 야놀자, 2020)
  > - 코로나 변이 바이러스 등장으로 *연말 국내 호텔 투숙 수요가 2020년 대비 3배이상 급증*하며, 2021년 연말 연휴 기간 결제 금액이 2020년 대비 호텔 25.6%, 펜션 18.3%, 캠핑 23.6% 상승하면서 호텔은 예약 건수 3.2배 증가 및 *입실일 기준 평균 28.4일 전 예약 완료*되는 현상을 보였다. (출처: 여기 어때, 2021)
    
* 이렇듯 코로나 19의 장기화로 많은 사람들은 국외 대신 국내 여행지를 찾고 있다. 하지만 다양한 여행 어플과 웹 사이트에서 제공하는 정보량의 과다로 빠르게, 원하는 숙소를 찾기 쉽지 않다. 특히 펜션의 경우 SNS(네이버, 인스타그램)에 올라온 리뷰를 통해 홍보되는 경우가 많아 일일이 찾아봐야하는 번거로움이 있다.

### 3) 프로젝트 목표

  (1) 2021년 기재된 네이버 여행 인플루언서의 블로그 리뷰를 크롤링하여 전국의 전국의 펜션 리뷰 데이터를 확보한다.
  (2) 데이터 전처리 및 시각화 패키지를 통해 탐색적 데이터 분석(EDA) 과정을 수행한다.
  (3) 지도 시각화 패키지를 활용해 펜션 리뷰 정보를 지도상에서 구현하며 최적의 정보전달 방법을 찾는다.

### 4) 프로젝트 성과

  (1) BeautifulSoup 패키지를 활용한 네이버 블로그 펜션리뷰 및 지리정보 Crawling
  (2) Raw data 전처리 및 Matplotlib, Seaborn 등 시각화 패키지 활용 EDA
  (3) 대한민국 행정구역 지리정보를 담고 있는 GeoJSON 파일에 대한 이해와 이를 활용한 Heatmap 시각화
  (4) Folium 패키지를 활용한 지도 시각화 및 HTML 기초 실습
