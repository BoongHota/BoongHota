# 어디있니 붕호타
- 근처 붕어빵, 호떡, 타코야끼 가게를 찾아주는 서비스에요.  
- 전국 붕세권, 호세권 그리고 타세권(?)까지 한 눈에 볼 수 있어요.
- 당신의 근처에 있는 가게를 등록하면 다른 사람들과 붕호타의 위치를 공유할수 있어요.
<br/>

### 찾고 싶은 가게 유형을 선택할 수 있어요!
<p align="center">
 <img width="800" src="https://media.vlpt.us/images/dolarge/post/b756bdff-a536-41d9-9f76-766282981d92/ezgif.com-gif-maker%20(6).gif"/>
</p>
<br/>

### 사장님뿐만 아니라 누구나 직접 가게를 등록하실 수 있어요!
<p align="center">
 <img width="800" src="https://user-images.githubusercontent.com/64346737/103617307-63d90d80-4f71-11eb-9d6b-89217b070b1c.gif"/>
</p>
<br/>

### 지도에서 내 주변 가게를 찾을 수 있어요!
<p align="center">
 <img width="800" src="https://user-images.githubusercontent.com/64346737/103617301-620f4a00-4f71-11eb-8f21-c0cf2cddc1ea.gif"/>
</p>
<br/>
                                                                                                                        
# 실행 방법
```git clone https://github.com/BoongHota/BoongHota.git  
cd server  
npm i  
npm start  
cd ../client  
npm i

(dev mode)
npm start

(prod mode)
준비중..
```
<br/>

# 디렉토리 구조
```
├ BoongHota  
 ├ client  
  ├ public  
  ├  src  
   ├  api  # Api call functions  
   ├  components  # UI components  
   ├  constants  # constant state  
   ├  hooks  # Custom hooks  
   ├  modules  # Redux actions, reducers, saga  
   ├  types  # type definitions  
   ├  App.js  
   ├  index.js    
 ├ server  
  ├  model # Data model(mongoose)  
  ├  types  # type definitions  
  ├  controller.js # Controller
  ├  db.js # Db connection  
  ├  index.js  
  ├  shopRouter.js # router  
```
<br/>

# 기술 스택
| Area | Tech Stack|
| - | - |
| Frontend | ![](https://img.shields.io/badge/TypeScript-3178c6?style=flat-square&logo=TypeScript&logoColor=white) ![](https://img.shields.io/badge/React-61dafb?style=flat-square&logo=React&logoColor=white) ![](https://img.shields.io/badge/Redux-764abc?style=flat-square&logo=Redux&logoColor=white) ![](https://img.shields.io/badge/Sass-cc6699?style=flat-square&logo=Sass&logoColor=white) |
| Backend | ![](https://img.shields.io/badge/TypeScript-3178c6?style=flat-square&logo=TypeScript&logoColor=white) ![](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=Node.js&logoColor=white) ![](https://img.shields.io/badge/MongoDB-47A248?style=flat-square&logo=MongoDB&logoColor=white) |
| 버전관리 | ![](https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=GitHub&logoColor=white) |
| 인프라 | ![](https://img.shields.io/badge/AWS-232F3E?style=flat-square&logo=Amazon%20AWS&logoColor=white) |
<br/>

# Wiki
- [Convention](https://github.com/BoongHota/BoongHota/wiki/Git-&-Github)
- [API docs](https://github.com/BoongHota/BoongHotaClient/wiki/API-%EB%AA%85%EC%84%B8%EC%84%9C)
- [어려웠던 점](https://github.com/BoongHota/BoongHota/wiki/%ED%94%84%EB%A1%9C%EC%A0%9D%ED%8A%B8-%EC%A7%84%ED%96%89%EC%8B%9C-%EC%96%B4%EB%A0%A4%EC%9B%A0%EB%8D%98-%EC%A0%90)
