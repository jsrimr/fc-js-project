# Fast campus Online JavaScript Project

[Slide](https://slides.com/woongjae/fc-javascript)

```
npm i
npm start
```

## 기능 
- 로그인
- CRUD 기능

## 쓸모
- 부트스트랩에서 가져온 html, css 기본 템플릿
- promise, async-await 등 기능 연습

## 한계점
- 프론트엔드만 구현됨
- api는 marktube.tv에 의존해야함

## 과제
- api 서버를 셀프구현해서 연결하기

## 깨달음
- async는 언제 쓰는가 : 통신 할 때 주로 쓴다. 통신하는 동안 다른 부분이 막히면 안되기 때문. async함수 안에서 꼭 기다려야 하는 부분 등이 있으면 그 부분에만 await 써준다. 그리고 통신 안하는 함수들은 그냥 일반함수 쓴다. 