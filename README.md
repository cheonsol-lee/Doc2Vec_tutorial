# Doc2Vec_tutorial

----------
### 1. 목적
* Document embedding을 이해하기 위해 네이버 영화 리뷰 데이터셋을 가지고 실습을 진행함.


----------
### 2. 특징
1. 불용어 처리
2. 형태소 분석
3. 시각화: Bokeh API


----------
### 3. 설치할 것

* from konlpy.tag import Okt : Okt 형태소 분석기 사용(트위터 제작)
* from gensim.models.doc2vec import Doc2Vec, TaggedDocument : Gensim 사용

![image](https://user-images.githubusercontent.com/28869864/117263489-48cdca00-ae8d-11eb-99aa-d10b244ec201.png)
(Bokeh 시각화 예시 - '제1공화국'은  '써드 스타 제1공화국'과 유사함)

