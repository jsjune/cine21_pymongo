# 크롤링과 데이터베이스 

* cine21 배우 랭킹 사이트 크롤링
  - 사이트 주소: http://www.cine21.com/rank/person/
  - 요청 방식 확인 방법: 크롬 개발자 모드로 들어가서, Network -> content 페이지의 요청 방식 확인 (Preserve log, All 체크)
    - Request URL: http://www.cine21.com/rank/person/content
    - Request Method: POST
    - Form data (payload)
      - section = 'actor'
      - period_start = '2020-12'
      - gender = 'all'
      - page = 1 

|num|과정|
|:---:|:---:|
|1~3|[라이브러리 import, mongodb 연결, 크롤링 주소 requests](https://github.com/jsjune/cine21_pymongo/blob/master/cine21_1~3.ipynb)|
|4|[배우 이름 추출](https://github.com/jsjune/cine21_pymongo/blob/master/cine21_4.ipynb)|
|5|[배우 상세정보 추출](https://github.com/jsjune/cine21_pymongo/blob/master/cine21_5.ipynb)|
|6|[배우 흥행지수와 출연영화 추출](https://github.com/jsjune/cine21_pymongo/blob/master/cine21_6.ipynb)|
|7|[수집한 데이터 기반 사전 만들기](https://github.com/jsjune/cine21_pymongo/blob/master/cine21_7.ipynb)|
|8|[여러 페이지의 배우 상세정보 추출](https://github.com/jsjune/cine21_pymongo/blob/master/cine21_8.ipynb)|
|9|[mongodb에 크롤링 데이터 저장](https://github.com/jsjune/cine21_pymongo/blob/master/cine21_9.ipynb)|
|final|[배우랭킹 및 상세정보 클롤링 및 mongodb 저장](https://github.com/jsjune/cine21_pymongo/blob/master/cine21_final.ipynb)|
