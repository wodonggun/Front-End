## VS Code 설치

> 개발하고자 하는 프로젝트의 단위는 폴더(=디렉토리) 단위
- 통합개발환경 IDE : Integrated development environment
- Extensions : 간단하게 플러그인으로, VS Code를 사용하면서 추가로 필요한 기능을 설치(확장)해서 사용할 수 있음.




## Extension 설치

1. Korean Language Pack 한국어 서비스 패키지 설치
2. Beautify 설치 : 바로가기키를 설정하여 자동 정렬 사용  
![image](https://user-images.githubusercontent.com/35188271/222061684-954b32ea-685e-4d73-b369-4d9861cf41b1.png)
3. Auto Rename Tag : 태그 앞뒤를 동시에 수정이 가능함.
4. Live Server : 웹페이지 로컬로 서버 동작
5. 공백(들여쓰기) 2칸으로 설정







## 동작 테스트

index.html
```HTML
<!DOCTYPE html>
<html lang="ko">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Document</title>
  <link rel="stylesheet" href="./main.css"></link>
  <style>
    div{
      text-decoration: underline;
    }
  </style>
</head>
<body>
  <div>Hello World!</div>
</body>
</html>
```
  
main.css
```CSS
div {
  color: red;
  font-size: 50px; 
}
```


## JS 동작 테스트

script헤더 추가 :   <script src="./main.js"></script>  


main.js
```js
let myName = "WDG";
let email = 'wodonggun@naver.com';
let hello = `Hello ${myName}?!`;

console.log(myName);
console.log(email);
console.log(hello);
```
  
크롬 -> 개발자 Mode에서 콘솔 로그 확인


## 아이콘 추가
![image](https://user-images.githubusercontent.com/35188271/222076890-adcbf559-47aa-429f-b9c7-c4951eaab38b.png)
`<link rel="icon" href="./favicon.png">`


## 이미지 추가

`<img src="logo.png" alt="">`
