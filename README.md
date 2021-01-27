# Cloud-Zero-DataAnalysis:beers:

>**클라우드 클리어 제로 시장 분석 및 판매전략 **

</br>

## 수행 기간: 2021.01.23 ~ 2021.01.27

</br>

## 데이터 분석 목적
- 불과 몇년 전만해도 인기가 없던 무알콜 맥주의 급성장을 확인할 수 있습니다.
- 클라우드 클리어 제로의 문제점에 대해서 확인할 수 있습니다.(맛 평가 등)
- 뉴스, 쇼핑몰 리뷰 크롤링을 통해 나타난 주요 키워드를 분석하여 다른 맥주와의 차별점, 단점을 분석할 수 있습니다.
- 클라우드 클리어제로의 판매전략, 개선점 등에 대해서 마켓팅을 할 수 있습니다.

## 크롤링 
- 무알콜 맥주 관련 뉴스 기사(네이버 뉴스)
- 클라우드 클리어 제로, 하이트 제로 쇼핑몰 리뷰(쿠팡)

</br>

## 사용 library
#### 뉴스 크롤링
- requests, bs4 
- pandas 
- datetime 
- nltk 
- wordcloud
- matplotlib
- pprint
- urllib.request
- Counter

#### 쇼핑몰 리뷰 크롤링
- time
- pandas
- selenium
- bs4
- requests
- matplotlib
- wordcloud
- Counter
- nltk


</br>

## 구현 순서
|                     |                                                                    |
|:-------------------:|:------------------------------------------------------------------:|
|      뉴스 크롤링     | 네이버 뉴스 크롤링 → 키워드 전처리 → 워드클라우드 제작 → graph 표현    |
|  쇼핑몰 리뷰 크롤링  | 쿠팡 맥주 리뷰 크롤링 → 키워드 전처리 → 워드클라우드 제작 → graph 표현  |
|                     | 

</br>

## 데이터 분석 자료_뉴스
#### 뉴스 키워드 워드클라우드_홈술 
![홈술](https://github.com/imeamin/Cloud-Zero-DataAnalysis/blob/master/%EB%89%B4%EC%8A%A4%ED%81%AC%EB%A1%A4%EB%A7%81/%ED%99%88%EC%88%A0.png?raw=true)


<br/>

***

<br/>

#### 뉴스 키워드 워드클라우드_혼술
![혼술](https://github.com/imeamin/Cloud-Zero-DataAnalysis/blob/master/%EB%89%B4%EC%8A%A4%ED%81%AC%EB%A1%A4%EB%A7%81/%ED%98%BC%EC%88%A0.png?raw=true)

<br/>

***

<br/>

## 데이터 분석 자료_쇼핑몰 리뷰(쿠팡)
#### 클라우드 클리어 제로 단어 빈도수 
![클라우드클리어제로_단어_빈도수](https://github.com/imeamin/Cloud-Zero-DataAnalysis/blob/master/readme_picture/%ED%81%B4%EB%9D%BC%EC%9A%B0%EB%93%9C%ED%81%B4%EB%A6%AC%EC%96%B4%EC%A0%9C%EB%A1%9C_%EB%8B%A8%EC%96%B4_%EB%B9%88%EB%8F%84%EC%88%98.JPG?raw=true)

<br/>

***

<br/>

#### 클라우드 클리어 제로 워드클라우드
![클라우드클리어제로_워드클라우드](https://github.com/imeamin/Cloud-Zero-DataAnalysis/blob/master/readme_picture/%ED%81%B4%EB%9D%BC%EC%9A%B0%EB%93%9C%ED%81%B4%EB%A6%AC%EC%96%B4%EC%A0%9C%EB%A1%9C_%EC%9B%8C%EB%93%9C%ED%81%B4%EB%9D%BC%EC%9A%B0%EB%93%9C.JPG?raw=true)

<br/>

***

<br/>

#### 클라우드제로 단어 빈도수 히스토그램
![클라우드제로 단어 빈도수_히스토그램](https://github.com/imeamin/Cloud-Zero-DataAnalysis/blob/master/readme_picture/%ED%81%B4%EB%9D%BC%EC%9A%B0%EB%93%9C%EC%A0%9C%EB%A1%9C%20%EB%8B%A8%EC%96%B4%20%EB%B9%88%EB%8F%84%EC%88%98_%ED%9E%88%EC%8A%A4%ED%86%A0%EA%B7%B8%EB%9E%A8.png?raw=true)

<br/>

***

<br/>

#### 클라우드클리어제로 단어 빈도수 파이 그래프
![클라우드클리어제로 pie graph](https://github.com/imeamin/Cloud-Zero-DataAnalysis/blob/master/readme_picture/%ED%81%B4%EB%9D%BC%EC%9A%B0%EB%93%9C%ED%81%B4%EB%A6%AC%EC%96%B4%EC%A0%9C%EB%A1%9C%20pie%20graph.JPG?raw=true)

<br/>

***

<br/>

#### 하이트 제로 단어 빈도수
![하이트제로_단어_빈도수](https://github.com/imeamin/Cloud-Zero-DataAnalysis/blob/master/readme_picture/%ED%95%98%EC%9D%B4%ED%8A%B8%EC%A0%9C%EB%A1%9C_%EB%8B%A8%EC%96%B4_%EB%B9%88%EB%8F%84%EC%88%98.JPG?raw=true)

<br/>

***

<br/>

#### 하이트 제로 워드클라우드
![하이트제로_워드클라우드](https://github.com/imeamin/Cloud-Zero-DataAnalysis/blob/master/readme_picture/%ED%95%98%EC%9D%B4%ED%8A%B8%EC%A0%9C%EB%A1%9C_%EC%9B%8C%EB%93%9C%ED%81%B4%EB%9D%BC%EC%9A%B0%EB%93%9C.JPG?raw=true)

<br/>

***

<br/>

#### 하이트 제로 단어 빈도수 히스토그램
![하이트제로 단어빈도수_히스토그램](https://github.com/imeamin/Cloud-Zero-DataAnalysis/blob/master/readme_picture/%ED%95%98%EC%9D%B4%ED%8A%B8%EC%A0%9C%EB%A1%9C%20%EB%8B%A8%EC%96%B4%EB%B9%88%EB%8F%84%EC%88%98_%ED%9E%88%EC%8A%A4%ED%86%A0%EA%B7%B8%EB%9E%A8.png?raw=true)



<br/>

***

<br/>

#### 하이트 제로 단워 빈도수 파이 그래프
![하이트제로_pie_graph](https://github.com/imeamin/Cloud-Zero-DataAnalysis/blob/master/readme_picture/%ED%95%98%EC%9D%B4%ED%8A%B8%EC%A0%9C%EB%A1%9C_pie_graph.JPG?raw=true)

<br/>

***

<br/>

## 역할 분담
- 👨‍💻용우중**자료분석 및 발표**
- 👨‍💻임혜민**자료분석**
- 👨‍💻엄태경**그래프 담당** 
- 👨‍💻최성준**PPT**

