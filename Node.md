# Node.js

NPM(Node Package Manager) - 다양한 패키지,모듈을 관리

- nvm 명령 설치 : https://github.com/coreybutler/nvm-windows/releases
![image](https://user-images.githubusercontent.com/35188271/214218854-a9d9a53d-a3e0-47a8-9382-27b03c00d93e.png)



- node.js 새 버전 설치 : `nvm install 12.14.1`
- node 버전 선택 : `nvm use 12.14.1`
- 노드 환경 구성 : `npm init -y`
- 패키지 pracel 설치 : `npm install parcel-bundler -D`
- 패키지 lodash 설치: `npm install lodash` (import , from 가능하도록)

```
npm install -D XXX
npm install XXX
해당 -D 옵션을 통해서 -D(=`--save-dev`)가 있으면 개발용에서만 사용하는 의존성 패키지임
```

- ^ 기호 : `^는 major버전 안에서 가장 최신버전으로 업데이트 가능. ex) ^12.14.1



- 콜백(Callback) : 실행 순서 보장  
![image](https://user-images.githubusercontent.com/35188271/214239989-1de19823-44b9-4299-8aca-6f0ee47f1d85.png)  




- 생성자 함수 : 생성자 함수는 일반 함수와 다르게 구분하기 위해 첫글자를 대문자로 사용함.
![image](https://user-images.githubusercontent.com/35188271/214289393-5a03d947-dac3-46bd-a1c7-f930c8a8cd40.png)

- 함수 추가 선언(`__proto__라는 객체내부에 ` 
![image](https://user-images.githubusercontent.com/35188271/214292590-a515b007-740e-4c8e-a204-49896632be52.png)


- this 범위 : normal은 일반 함수(부모까지 참조함)지만, arrow는 화살표 함수로 this의 범위는 클래스 전체(객체 내부)가 아니라 함수 선언된 블록내부만 참조함.
![image](https://user-images.githubusercontent.com/35188271/214289963-3c18c068-45e9-4596-b882-aa76a655cc91.png)  
![image](https://user-images.githubusercontent.com/35188271/214291197-2f7a6081-f2a7-44ae-b720-39f1183c9b75.png)  
  
- 화살표 객체 활용 : 화살표 함수는 자신이 선언된 함수 블록내부를 this로 참조할 수 있음.
![image](https://user-images.githubusercontent.com/35188271/214291686-b2486a43-ceb5-4987-a5cf-f5d671c1fe8e.png)
