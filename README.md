## Review analysis: apple watch VS galaxy watch
#### 목적: 가장 보편적인 웨어러블 기기의 쿠팡 리뷰 비교
#### 분석툴: selenium, mecab, wordcloud, sklearn, pyLDAvis
#### 결론: 텍스트마이닝으로만으로 유의미한 결론을 얻을 수 없었음.

### 갤럭시워치
불용어: 이, 등, 좋, 워치, 갤럭시, 기능, 구매, 너무, 사용, 정도, 시계

####  wordcloud
![image](https://github.com/alwls5773/side_project_2/assets/66359601/57a62ff6-79a9-4cb2-a548-228e0c8d84d0)

가장 주목되는 단어는 충전, 생각, 배터리, 만족, 운동으로 확인됨.

#### 빈도 
![image](https://github.com/alwls5773/side_project_2/assets/66359601/15805cb3-b1c1-42ab-a8f1-be7a5305fe05)

구간, 학교, 채팅, 다소, 사과, 최적화, 스텐, 지정, 스테인리스, 제어가 리뷰에서 많이 나타남.

#### TF-IDF
![image](https://github.com/alwls5773/side_project_2/assets/66359601/be30fd73-6522-45b4-acdb-1c73fefc4d6d)

TF-IDF는 내요, 조카, 셀룰러, 조아, 콘센트, 다루, 반나절, 어서, 괜히, 내리 순으로 높은 것을 확인할 수 있음. 

#### LDA
3개

### 애플워치

불용어: 이, 등, 신고, 워치, 애플, 구매, 사용, 기능, 너무, 시계, 정도

#### wordcloud
![image](https://github.com/alwls5773/side_project_2/assets/66359601/d3d735cc-08a3-4b64-a0d4-61bfa82d6edc)

가장 주목되는 단어는 고민, 만족, 생각으로 확인됨.

#### 빈도
![image](https://github.com/alwls5773/side_project_2/assets/66359601/1eda6181-4c30-4dee-af7c-6df3fe47f7fe)

밀레, 니즈, 외관, 플러스, 존재, 다이소, 습관, 미루, 일요일, 환경이 리뷰에서 많이 나타남.

#### TF-IDF
![image](https://github.com/alwls5773/side_project_2/assets/66359601/2060c6b0-08d1-4e64-bcbb-1635e21bf08a)

TF-IDF는 치료, 딸아이, 분실, 체격, 아깝, 변동, 변화, 실패, 착하, 의미 순으로 높은 것을 확인할 수 있음. 

#### LDA
3개

##### 주의

갤럭시워치와 애플워치 각각 1400, 1260 개씩 리뷰를 크롤링했지만, 실제 유의미한 리뷰 개수는 갤럭시 워치가 더 많았음. 또한 크롤링할 수 있었던 리뷰 수 자체가 적은 문제가 있었음. (가장 최근에 나온 3가지 버전의 스마트워치의 500개의 리뷰를 모았음)

### 결론
갤럭시워치와 애플워치의 쿠팡 리뷰를 크롤링하여 비교해보았지만, 유의미한 비교가 어려웠음. 하지만 워드클라우드를 보면 두 제품 모두 '고민'이라는 단어가 리뷰에 많이 포함되어 있음을 알 수 있음. 이를 통해 스마트워치를 구매할 때 소비자들이 많은 고민을 거쳐 구매까지 도달한다는 것을 알 수 있음. 
