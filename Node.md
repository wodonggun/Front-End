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


