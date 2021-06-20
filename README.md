# Crawling
대전광역시의 주요 관강지 15곳에 대한 관광 리뷰 데이터를 구축하기 위한 크롤링 레포지토리입니다. 

## 데이터
1. 주요 관광지 총 15곳
- 공공데이터포털에 업로드 된 '대전광역시 관광명소'의 11곳
  - 계족산황톳길
  - 대전문화예술단지
  - 대청호반
  - 동춘당
  - 뿌리공원
  - 오월드
  - 유성온천
  - 으능정이문화의거리
  - 엑스포 과학공원
  - 장태산 휴양림
  - 한밭수목원
- 추가적으로 대전 방문 유입이 많을 것으로 예상되는 관광명소 4곳
  - 국립중앙과학관
  - 대전시민천문대
  - 수통골
  - 성심당 
  
2. 2012년 이후 데이터 

## 크롤링 플랫폼    
  (1) 구글 맵 리뷰 : [selenium, BeautifulSoup](https://github.com/JeongCheck/Crawling/blob/main/googleMapReview%20.ipynb)     
    - 참고 : http://egloos.zum.com/mcchae/v/11281390, \[김경록서영덕, 2018, "한입에 웹 크롤링", 비제이퍼블릭]    
  (2) 네이버 블로그 : [네이버 검색 API](), [selenium](), [BeautifulSoup]()   
    - 참고 : https://github.com/xotrs/naver-blog-crawler, http://www.donsdev.me/devlogs/27
    
### 이슈 사항
- 네이버 블로그 검색 API가 중복 데이터를 불러오는 등의 문제가 있었고, selenium, BeautifulSoup을 사용하면 html이 보이지 않았다.
- 따라서 프로젝트에는 구글 맵 리뷰 데이터만 사용했다. 
