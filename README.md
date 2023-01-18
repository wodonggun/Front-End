# Front-End


## VS Code 설치

- Auto Rename Tag : 앞뒤 태그 동시 수정  
![image](https://user-images.githubusercontent.com/35188271/212522488-cc91a896-93e3-45c2-b572-18b787687b44.png)  
![image](https://user-images.githubusercontent.com/35188271/212522475-9aab6f34-2540-438f-b8cb-e0d37a024c44.png)  

- Live Server : 크롬 Web 열기  
![image](https://user-images.githubusercontent.com/35188271/212522665-a2fe6569-2a3f-4b51-84d7-f92ce3209465.png)  

- Beautify : 자동 정렬  
![image](https://user-images.githubusercontent.com/35188271/212522817-65f0d1ac-811b-49d9-b201-8976c9fe28ed.png)  


- `!+Tab키` : HTML 자동완성  
![image](https://user-images.githubusercontent.com/35188271/212522998-706f89aa-ed08-4b9f-9bf6-7ad502e3d0dc.png)




## HTML

![image](https://user-images.githubusercontent.com/35188271/212523065-db69a1fd-7354-441f-872f-7f1d1e10bc0b.png)
![image](https://user-images.githubusercontent.com/35188271/212523458-16299ff3-8538-48f6-9fbf-62a8dfcd5083.png)
![image](https://user-images.githubusercontent.com/35188271/212523505-a7462afd-b090-454f-986d-b382c079088a.png)
![image](https://user-images.githubusercontent.com/35188271/212523510-3a61872f-c31b-401c-970c-f2e6ebceed1a.png)
![image](https://user-images.githubusercontent.com/35188271/212523716-5490543e-adc9-4f32-9c60-9401ca8162ad.png)
![image](https://user-images.githubusercontent.com/35188271/212524106-50844f38-fea2-4f9f-bbde-327ece6295ca.png)


![image](https://user-images.githubusercontent.com/35188271/212541824-648e6c2a-cb20-4836-b9a4-7290345c99d8.png)
![image](https://user-images.githubusercontent.com/35188271/212542138-b2cbd248-334a-43ee-aa2d-81ba6b87ff45.png)

- 인라인 요소 : 글자
![image](https://user-images.githubusercontent.com/35188271/212542365-31f19f7c-09f9-4e2d-87f9-215a9fd2dace.png)  

- margin `외부여백`, padding `내부 여백` : 글자는 좌우만 여백을 가질 수 있고, 위 아래는 불가능.
![image](https://user-images.githubusercontent.com/35188271/212542568-0641b440-d36e-42d4-a804-302e09c8824b.png)


- 블록 요소 : 상자 범위


## 핵심 요소

`블록(상자) 요소` : 세로로 정렬되는 요소들로, 가로는 최대사이즈를 가지려고함(즉 세로로 요소들이 정렬됨)
- `<p>` : Parapgraph 문장을 의미하는 요소
- `<h>` : Heading 제목을 의미함(h1,h2,h3등)
- `<ol>` : Ordered List 순서가 필요한 목록
- `<ul>` : UnOrdered List 순서가 필요없는 목록
- `<li>` : List Item 목록 내, 각 항목
- `<input>` : 데이터 입력 요소(type="text","checkbox", "radio") (value="대한민국" 기본값) (placeholder="000-0000-0000" 힌트값) (disabled)
- `<table>` : 행 열의 집합  
![image](https://user-images.githubusercontent.com/35188271/212543949-e1b2ce87-15c7-42e9-a1e1-581c7a972058.png)  
- 

`인라인(글자) 요소
- `<img>` : Image 이미지를 삽입하는 요소(src 필수속성 지정해야함,alt라는 이미지의 이름도 지정해야함)
- `<a>` : Anchor 페이지로 이동하는 하이퍼링크를 지정(target="_blank"는 새탭으로 열기)
- `<span>` : 의미가 없이 구분을 위한 요소
- `<br/>` : Break 줄바꿈 요소
- `<label>` : 라벨 가능 요소의 제목(checkbox 글자삽입) (기본 체크 checked/> )  
![image](https://user-images.githubusercontent.com/35188271/212543791-0d1a0495-1b99-4654-8ff3-474d7b5ec3db.png)  
![image](https://user-images.githubusercontent.com/35188271/212543885-b7c55006-8a35-4bfc-b7aa-77fb963b6b18.png)  

- `class` : 요소의 중복가능한 이름
- `id` : 요소의 고유한 이름(중복되어서 사용하지않고, 특별한 값에 고유해야함 = 중복되어도 정상동작하고, css모두 적용됨)
- `data` : 요소에 데이터그룹 지정
![image](https://user-images.githubusercontent.com/35188271/213172900-d3bcbba6-f9d5-4a28-a112-eeab7648811e.png)

- `선택자{속성:값; 속성:값;} = span{color:red; margin: 20px;}` : 선택자는 원하는 요소의 css이름

![image](https://user-images.githubusercontent.com/35188271/213180609-4a1adaa1-8143-4db2-bf5c-35a47de45a86.png)
![image](https://user-images.githubusercontent.com/35188271/213180630-e16a0275-32ac-4030-b6b1-1d129e9848b4.png)
![image](https://user-images.githubusercontent.com/35188271/213180643-fd855162-0919-4ab0-9f4e-d0383c7995e9.png)
![image](https://user-images.githubusercontent.com/35188271/213180663-9207f365-b759-4f0e-ba18-537a928841d5.png)
![image](https://user-images.githubusercontent.com/35188271/213180681-1abb8764-4056-4d39-aec3-024edfd9244f.png)
![image](https://user-images.githubusercontent.com/35188271/213180696-8cf8322f-a6bf-4a91-bea8-484a9c1a95ab.png)
![image](https://user-images.githubusercontent.com/35188271/213180707-48e315c3-aec7-4f51-931c-cf5827631b6a.png)
![image](https://user-images.githubusercontent.com/35188271/213180726-3814869f-066c-4ca7-add2-59bfa2ace050.png)
![image](https://user-images.githubusercontent.com/35188271/213180744-8b5d3b08-774e-4608-a380-a01365faac41.png)
![image](https://user-images.githubusercontent.com/35188271/213181991-36b6b28f-13a1-4215-88ec-1223f3cadbd4.png)
![image](https://user-images.githubusercontent.com/35188271/213182006-520478db-d3f4-4ee3-82b8-d4b88a4ecb26.png)
![image](https://user-images.githubusercontent.com/35188271/213182037-a5f270d6-8b86-4e9c-a762-1c96487cb890.png)
- `focus` : 대표적으로 input태그가 가능하고, div같은 경우에 불가능 하지만 아래와 같이 tabindex="-1"을 주게되면 focus기능 활성화.
![image](https://user-images.githubusercontent.com/35188271/213182991-bdbf5d59-4370-4b96-a316-7912bdd16814.png)
![image](https://user-images.githubusercontent.com/35188271/213185454-4823d760-ac9b-487f-9da5-da79c0577d9f.png)
![image](https://user-images.githubusercontent.com/35188271/213185479-bd4e5d84-1854-4c3f-9512-9c16c85314c9.png)
![image](https://user-images.githubusercontent.com/35188271/213185874-40f9163e-7ac6-4959-883d-b460722d776e.png)
![image](https://user-images.githubusercontent.com/35188271/213185976-555d965d-2895-41e6-b099-d5d40f3ae89b.png)
![image](https://user-images.githubusercontent.com/35188271/213186000-da4881d5-33c2-4cd5-acc0-aea9b2f9f01d.png)


- `스타일 우선순위` :   
![image](https://user-images.githubusercontent.com/35188271/213190257-571f26b5-5313-4fe2-a8d9-69e435daf0e0.png)
![image](https://user-images.githubusercontent.com/35188271/213190230-0ab7f25e-7326-418b-8fc0-2f9504c86a61.png)



