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




# 상대 경로 vs 절대 경로

![image](https://user-images.githubusercontent.com/35188271/222871125-bc90fd9b-1b3f-4542-a53c-d861bbde550b.png)

- `상대 경로` : 상대적인 경로로, 현재 자신의 위치를 기준으로 함(`./testApp/favicon.svg`)
- `절대 경로` : 지금 현재 파일(폴더)의 위치가 아닌, 처음 경로(root)부터 원하는 경로까지 모든 경로를 다 입력함(`C:\Users\User\Project\testApp\index.html`)



## 예시

![image](https://user-images.githubusercontent.com/35188271/222871373-49c0d2a4-af8d-48f1-80ee-dd3487a4d865.png)

![image](https://user-images.githubusercontent.com/35188271/222871375-5437e4d2-7e1c-4724-9735-6e43d1aa2b2d.png)

![image](https://user-images.githubusercontent.com/35188271/222871385-9da8d203-eca3-4858-99b6-c1641bcde463.png)

