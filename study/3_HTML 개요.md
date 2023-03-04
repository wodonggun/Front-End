# 기본 문법

![image](https://user-images.githubusercontent.com/35188271/222873372-79228e2d-656c-4a04-83fb-ba6d74f14cce.png)  
> HTML에서 태그는 내용의 시작점과 끝점을 표시해주는 역할

요소는 앞뒤Tag+내용
앞의 Tag는 시작(열린)Tag라고 부르며, 뒤의 Tag는 종료(닫힌)Tag라고 부름.



## 빈 태그

![image](https://user-images.githubusercontent.com/35188271/222873535-d7f19885-c668-4dbb-aba0-f5a6d05bb52b.png)  
빈 태그의 닫힘을 표시하지않으면 편하다는 장점이 있지만, 사람이 이게 빈태그인지 열고닫는 태그인지 구분하기가 힘들다는 단점이 있음.

XHTML,HTML5는 엄격하게 관리하기 위해서 빈 태그라도 `/(슬래쉬)`를 붙여서 사용함.
엄격하다 = 시작과 끝을 나타내던지, 시작과 동시에 끝태그를 바로 붙이면서 명시적으로 태그의 시작과끝이 같다는것을 알려줌 = 컴퓨터가 명확하게 인지하고 오류를 줄일 수 있음.


## 이미지 태그
- `태그의 속성` : 태그만으로는 다양한 설정에 제약이 생겨 속성을 추가하여 사용함.
![image](https://user-images.githubusercontent.com/35188271/222873713-eea11b56-ea14-4f3d-8565-289bb745e472.png)
--- 
![image](https://user-images.githubusercontent.com/35188271/222873754-2b7e387a-6a31-45d2-816c-aab926e621ae.png)
--- 
![image](https://user-images.githubusercontent.com/35188271/222874594-d6e33ab6-75bc-4c9b-9544-4a16830b9c7e.png)



## input 태그

![image](https://user-images.githubusercontent.com/35188271/222873853-237b81be-919e-42f8-b111-51df26bea218.png)
---
![image](https://user-images.githubusercontent.com/35188271/222873813-1e2a974d-ac1b-4fa8-95e7-9e997016d4b0.png)
---
![image](https://user-images.githubusercontent.com/35188271/222873822-c0f146da-63e1-447d-bce6-ec22dabdfd0b.png)


# 글자와 상자

![image](https://user-images.githubusercontent.com/35188271/222873899-a2533570-ce9d-4848-8a39-e86e5d24c6d5.png)

```
화면에 구성하고, 출력하는 특성은 크게 두가지(인라인,블록)요소로 구분된다.
인라인 요소 : 글자 (span,img,a,
블록 요소 : 상자=레이아웃 (div,h1,p,ul,li,
```


## 인라인 요소
![image](https://user-images.githubusercontent.com/35188271/222874004-5e238019-715b-417e-abfe-c4c2e1081f01.png)
--- 
![image](https://user-images.githubusercontent.com/35188271/222874166-3d5a52b6-14f0-434e-8743-a7de3c3fe55f.png)
--- 
![image](https://user-images.githubusercontent.com/35188271/222874298-32dad3b1-4a98-4390-89b6-e58b8d98015c.png)
---
- 인라인 요소 안에는 블록요소(div)를 넣을 수 없음(글자 안에 상자를 담는다는게 불가능)
![image](https://user-images.githubusercontent.com/35188271/222874326-3d4ca305-73f0-4fc8-8b9f-813166eb7937.png)
--- 




## 블록 요소
- `div태그` : div는 대표적인 블록 요소로 특별한 의미가 없지만 서로 구분하기 위한 요소로 기본적으로 사용함.
![image](https://user-images.githubusercontent.com/35188271/222874360-afe44555-5d67-4c70-8ac8-6a46cae5f3a4.png)
---  
![image](https://user-images.githubusercontent.com/35188271/222874395-d106154e-baf8-4f31-900b-1f08bc8f4079.png)
---
![image](https://user-images.githubusercontent.com/35188271/222874450-aa0ab33f-2d48-4cfa-b9ac-0a11cf6e6060.png)
--- 
![image](https://user-images.githubusercontent.com/35188271/222874432-82f2dd14-d395-4461-81ab-95cdc783417e.png)

