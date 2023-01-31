# REACT

- React란 ? : JavaScript를 쉽고 편하게 사용할 수 있게하는 라이브러리
- CSR(Client Server Side Rendering) : 
![image](https://user-images.githubusercontent.com/35188271/215242306-28386260-d257-4a0d-8994-713a5cb92800.png)  



- React.Dom.render ( );는 React에서 작성한 JS,JSX를 HTML_Element로 연결해주는 역할  
![image](https://user-images.githubusercontent.com/35188271/215242576-dea5e7e1-1cc4-4b9b-aade-e1b02efe669a.png)





## 시작

- npx ? : npm 5.2.0이상에서 지원하는 최신라이브러리를 가져오는 명령어

```
npm install 14.16.1
npm list
npm use 14.16.1

npm init -y
npx serve
```

- JSX란?  
![image](https://user-images.githubusercontent.com/35188271/215265243-5049eac1-1690-4ea9-9cc4-0560c2b86eb0.png)


- LifeCycle  
![image](https://user-images.githubusercontent.com/35188271/215265329-5b3474b6-7009-4a45-8479-3c4af36b1a0c.png)


- 리엑트 생성 : npx create-react-app tic-tac-toe
- react 실행 : npm start
- production 빌드 : npm run build  
npm install -g serve  
npx serve -s  build  


- webpack  
![image](https://user-images.githubusercontent.com/35188271/215266314-3bc5330e-8be8-4b18-9f38-1bc13f5f76f1.png)

- npx eslint --init
![image](https://user-images.githubusercontent.com/35188271/215266412-9afef191-4d63-45cf-b283-058543107c5e.png)



- SPA(Single Page Application) : 기존의 웹은 화면마다 페이지를 새로 불러와야 하지만, SPA는 원하는 부분만 바꾸고 새로 리랜더링 할 수 있다. Virtual DOM 덕분임.
- react-router-dom : `npm i react-router-dom` 라우터를 직접 설치해줘야함.


- 라우팅  URI요소
![image](https://user-images.githubusercontent.com/35188271/215274518-d51acceb-e896-4758-8312-7266ac74d695.png)  
![image](https://user-images.githubusercontent.com/35188271/215274596-10b1154d-8384-49ee-8059-7c45bd8ee1e5.png)
- 라우팅 QueryString
![image](https://user-images.githubusercontent.com/35188271/215274544-5d1f862a-fe7a-4a1a-94dc-a1ea9e0897aa.png)


- 리다이렉트 : Login==true일때 Main페이지로 이동하고, false일때는 Login페이지로 이동하고 싶을때 
![image](https://user-images.githubusercontent.com/35188271/215275503-8135e49b-97c8-4341-a87a-03cfd00bde80.png)
