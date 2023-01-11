# DATATHON
<br>

## 목차
  - 팀 소개
    - 팀 이름
    - 팀원
  - 데이터
    - 데이터
    - 데이터 소개  
  - 목표
  - 스케줄
<br>

## 팀 소개
### 팀 이름 : 대글러
### 팀원
  1. 고도환
  2. 김태현
  3. 

<br>

## 데이터
  - 데이터
    - 소상공인 데이터(https://www.data.go.kr/data/15083033/fileData.do)
    - 상권 영역 데이터(https://data.seoul.go.kr/dataList/OA-15560/S/1/datasetView.do)
    - 매출 추정 데이터(https://data.seoul.go.kr/dataList/OA-15572/S/1/datasetView.do)
  - 데이터 소개 : 영업 중인 전국 상가업소 데이터를 제공합니다.(상호명, 업종코드, 업종명, 지번주소, 도로명주소, 경도, 위도 등)
<br>

## 목표
  - 데이터 탐색을 통해서 패턴 및 특성을 찾는다.
  - 데이터를 통해서 새로운 니즈를 확인해본다.
  - 대형 프랜차이즈별 입점 전략을 분석해본다.
 
## 목표2(7.26PM)
  - 서울에는 커피점이 많이 있다는 것을 확인했다. -> 커피라는 특성자체때문에 많은 것일수도 있기 때문에 근거필요 -> 다른지역은 어떤 음식점이 많은지 확인해볼 것 
  - 커피로한다면 지역별로 경도,위도 받아서 지도에 매출별로 지도에 표시 매출많으면 마커나 원?을 더 크게 만들필요있음
<br>

## 스케줄
  - 07/26
    - 오전 : OT
    - 오후
      - 데이터 확인 및 정리
        - 음식점 데이터로 축소
        - 음식점 종류별로 분류  
  - 07/27
    - 오전
    - 오후  
  - 07/28
    - 오전
      - 끝내기(정리포함)
    - 오후
      - 프로젝트 제출  
  - 07/29
    - 최종 발표
   
 
 ## 임시 작업란
  - 위도경도 지도표시
    - https://velog.io/@eodud0582/Folium -> 이거 잘 안됨
      - 해결책
        - https://github.com/python-visualization/branca/issues/81
        - https://nbviewer.org/ 
    - https://parkgihyeon.github.io/project/geocoding-api/

<br>

 ## 상권 영역, 상권 매출, 소상공인 데이터를 가지고 진행
  - groupby를 통해 원하는 컬럼과 숫자 데이터를 합칠 수 있다.
  - 상권 영역의 area를 보며 매출과 비교해본다.

 ## 참고자료
  - 판다스 : https://wikidocs.net/book/4639
  - 좌표변환 : https://m.blog.naver.com/wideeyed/221243506770
  - 깃에서 맵 안나오는 문제 해결 : https://nbviewer.org/
