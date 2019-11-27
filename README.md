# 아두이노 미세먼지 측정기

![77106973_1421066121383316_2152781391375368192_o](https://user-images.githubusercontent.com/1307187/69721087-6d315d00-1157-11ea-9886-3e318e55cd36.jpg)

![78622331_1421066111383317_1142797308912467968_o](https://user-images.githubusercontent.com/1307187/69721088-6d315d00-1157-11ea-988a-9141f625a431.jpg)

소스코드 받아서 사용하면 큰 문제 없음. 다만 라이브러리를 소스에서 제공해주는 버전으로 사용해야 정상 작동함. 예를 들어 DHT11 라이브러리를 라이브러리 매니저에서 다운받아 사용할 경우 같은 이름의 라이브러리인데도 불구하고 값이 이상하게 나오고 오동작 하는 것을 경험하게 됨

아두이노 스케치에서 13번 소스를 연 다음 크리스탈 LCD와 DHT11 라이브러리를 포함하기를 zip파일 지정해서 가져온 후 컴파일해서 넣으면 됨.  

## 사용키트 
키트에는 아두이노가 포함되어 있지 않기 때문에 측정기 키트 외에 아두이노를 하나 더 사야 한다. 호환품도 잘 동작함. 키트에 추가로 아두이노를 익힐 수 있는 부품들이 좀 더 있음. (LED나 초음파센서나 뭐 그런 기초적인 것들)
[아두이노 미세먼지 측정기 추가팩 키트 교재포함 (정밀편)](http://mechasolution.com/shop/goods/goods_view.php?goodsno=583049&category=)
[아두이노 우노 R3 호환보드 (Arduino uno R3) / 우노보드 / 우노 보드](http://mechasolution.com/shop/goods/goods_view.php?goodsno=71796&category=145015001)

## 조립방법
["미세먼지 측정기 아두이노 프로젝트" 에 대한 PDF 매뉴얼](https://cafe.naver.com/mechawiki/3909)
위 게시물에서 다운로드. 키트에 책자가 들어있는데 이것과 같은 버전.

## 소스코드
[https://cafe.naver.com/mechawiki/3858](https://cafe.naver.com/mechawiki/3858)

## DHT11 사용법 
[DHT11 아두이노 온도, 습도 센서 알아보기 / 아두이노 코딩 교육](https://m.blog.naver.com/PostView.nhn?blogId=roboholic84&logNo=221186233842&proxyReferer=https%3A%2F%2Fwww.google.com%2F)

[아두이노 온습도 센서(DHT11) 사용하기](http://www.iamamaker.kr/ko/tutorials/arduino/%EC%95%84%EB%91%90%EC%9D%B4%EB%85%B8-%EC%98%A8%EC%8A%B5%EB%8F%84-%EC%84%BC%EC%84%9Cdht11-%EC%82%AC%EC%9A%A9%ED%95%98%EA%B8%B0/)
