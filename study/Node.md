# Node.js

NPM(Node Package Manager) - 다양한 패키지,모듈을 관리

- nvm 명령 설치 : https://github.com/coreybutler/nvm-windows/releases
![image](https://user-images.githubusercontent.com/35188271/214218854-a9d9a53d-a3e0-47a8-9382-27b03c00d93e.png)



- node.js 새 버전 설치 : `nvm install 12.14.1`
- node 버전 선택 : `nvm use 12.14.1`
- 노드 환경 구성 : `npm init -y`
- 패키지 pracel 설치 : `npm install parcel-bundler -D`
- 패키지 lodash 설치: `npm install lodash` (편리한 모듈 제공)

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


- Foreach, Map : 둘다 반복하지만 foreach는 실행만 가능하고(할당불가능), Map은 반환값을 통해서 할당 가능.  
![image](https://user-images.githubusercontent.com/35188271/215117162-690eb810-98b9-44b7-8860-ac85a4d4193e.png)  
- 화살표 함수를 사용하면 return대신 ()를 통해서 함수의 반환값을 지정 가능 
![image](https://user-images.githubusercontent.com/35188271/215117608-287734e9-7d21-41a6-9b3f-835ba2446397.png)  
- Splice : splice(변경할 index, 삭제할 갯수, 추가할 데이터)
![image](https://user-images.githubusercontent.com/35188271/215120668-e89e31a5-139e-4484-bc49-01f90772a1b0.png)


- 주소참조 : const a = object.assign(A,B) A에 B를 덮어쓰고 A주소를 반환.  
- 값참조 : const a = object.assign({},A,B) {}에 A와 B를 값을 덮어쓰고 새로운 주소를 리턴.  
- 해시키 탐색
![image](https://user-images.githubusercontent.com/35188271/215123311-f89236a0-5c0b-47a1-aa35-7be70d8294bb.png)  

- 전개연산자 : 객체를 출력하지않고, 배열 값들을하나씩 출력(...fruits를 통해서 fruits의 모든 배열값들을 하나씩 출력)
![image](https://user-images.githubusercontent.com/35188271/215125585-161b39e5-3fb9-4d9b-bc84-4d671e9f5abe.png)
![image](https://user-images.githubusercontent.com/35188271/215125814-561df882-ec35-46db-b2f6-0dda7edc8b24.png)

- 데이터 불변성 : `let c`새로운 변수를 선언해줘도, 기존에 a변수가 1이라는 값을 가지고 있어서 c변수에 a메모리를 참조시킴....왜..?
![image](https://user-images.githubusercontent.com/35188271/215127198-92b62c15-0f8f-4167-a4a6-157735b7a820.png)

```js
const user = {
  name : 'Woo'
  age : 85,
  emails: ['woodg@gmail.com']
}
const copyUser = {...user};  // <-- 여기서 copyUser라는 객체는 새로운 메모리에 할당하지만, 그 내부의 name,age,emails들은 기존 users의 메모리를 참조하게생성됨.....
//깊은복사 하고싶다 : lodash활용해서 cloneDeep(user)를 사용
```

- 정규식(regexp 생성)
![image](https://user-images.githubusercontent.com/35188271/215232868-79ec7cf3-3039-4965-8ba0-bf1597831c3b.png)




