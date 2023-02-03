# 리엑트 배포

```
    git clone https://github.com/xid-mark/tic-tac-toe.git  
    cd .\tic-tac-toe\
    nvm use
    nvm install 10.16.3 
    npm ci  (패키지 설치)
    npm run build (배포용 build폴더 생성)
    npm install serve -g (
    serve build (그냥 배포)
    serve -s build (어떤 요청에 응답이 없는 루트인경우 index.html으로 자동 라우팅)
```

aws s3 -> 버킷생성 -> 있는그대로 제목만 짓고 생성  
-> 버킷객체 클릭후 업로드 -> build폴더 안의 파일+static폴더 전체 업로드  
다시 버킷 -> 속성탭 -> 맨하단의 정적웹사이트 호스팅 선택 -> 대충입력 index.html

- 퍼블릭차단 비활성화  
![image](https://user-images.githubusercontent.com/35188271/216589846-8c2309ec-a87c-458a-b8cb-3772079a4c3b.png)

- 버킷정책 수정  
![image](https://user-images.githubusercontent.com/35188271/216590741-da361896-f02b-47e2-8027-3793a3358198.png)  
```
{
    "Version": "2012-10-17",
    "Statement": [
        {
            "Sid": "PublicReadGetObject",
            "Effect": "Allow",
            "Principal": "*",
            "Action": "s3:GetObject",
            "Resource": "arn:aws:s3:::react-web-app-test-woo/*"
        }
    ]
}
```
