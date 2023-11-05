# **Wordy**
<br />


**Wordy는 사용자 중심의 영어 학습 플랫폼으로, 어디서나 편리하게 영어 단어를 학습하고, AI 기반의 문법 교정 서비스를 이용할 수 있도록 설계되었습니다.**

**영어는 전 세계적으로 가장 널리 사용되는 언어 중 하나이지만, 많은 사람들이 영어 학습에 어려움을 겪고 있습니다. 특히 단어 학습과 문장 구성에 대한 어려움이 크게 느껴집니다. 이러한 배경에서, Wordy는 사용자들이 효과적으로 영어 단어를 학습하고, 학습한 단어를 바탕으로 문장을 구성하는 연습을 할 수 있는 서비스를 제공하고자 탄생하였습니다.**

**또한, 자신이 작성한 문장이 올바른 문법으로 이루어져 있는지 확인하는 것은 영어 학습자에게 큰 어려움입니다. 이에 Wordy는 AI 기반의 문법 교정 기능을 도입하여, 사용자들이 영어 작문을 쉽고 정확하게 교정받을 수 있도록 하였습니다.**

**뿐만 아니라, Wordy는 사용자의 학습 동기를 높이기 위해 개인별 학습 진도율과 랭킹 시스템을 제공합니다. 이를 통해 사용자는 자신의 학습 상황을 쉽게 파악하고, 다른 사용자와의 랭킹을 통해 경쟁 의식을 느끼며 학습에 재미를 느낄 수 있습니다.**

**Wordy는 사용자의 영어 학습을 쉽고 재미있게 만들어주는 플랫폼으로, 사용자들이 영어에 대한 자신감을 높이고, 세계와 소통할 수 있는 기회를 제공하고자 합니다.**

<br />
<br />



## **프로젝트 기간**

- 2023.10.02 ~ 2023.11.04 (5주)

<br />


## **프로젝트 팀원 및 역할 분담**

| 이름  |       역할       | 기여도 |
|:---:|:--------------:|-|
| 진채영 |    팀장/ 풀스택     |  - 카카오 소셜 로그인 [백/프론트]<br /> - 학습 유저 랭킹 API [백/프론트]<br />- 클라이언트 아키텍처 및 배포<br />- 커스텀 및 학습 카테고리 단어장 클라이언트 CRUD<br />- React query를 통한 상태관리<br />- 커스텀 Hook을 통한 디바운스 적용 상태관리<br />- 페이지네이션 컴포넌트 구현<br />- 회원가입 및 로그인 페이지 에러 해결 및 구현<br />- 소셜 로그인 유저 이메일 추가 에러 해결 및 구현<br />- Figma를 통한 ui 기획<br />- Viewport 모바일용 버튼 생성 |
| 임재홍 |    풀스택 / AI    |  - 파이썬 FastAPI 서버 아키텍쳐 설정 및 배포<br />- 대화문 생성 api 구현 및 번역 api 연동<br />- 문법 설명 api 구현<br />- 대화문 생성 페이지 구현<br />- 학습완료 페이지 → 대화문 생성 연동 |
| 정현수 | 풀스택 / 데이터 / AI |   -학습 데이터 수집 및 전처리<br />-AI 모델 학습<br />-fine-tuned 모델 pipeline 배포<br />-db 데이터 전처리<br />-파이썬 문법교정 api 생성 (FastAPI)<br />-저장소 페이지 구현<br />-검색 컴포넌트 생성<br />-즐겨찾기 컴포넌트 생성<br />-커스텀 모달 생성<br />-문법 교정 페이지 구현 |
| 박영현 |      프론트       |   - 단어 학습 페이지 구현<br />- 체험 학습 페이지 구현<br />- 메인 서비스 전체 레이아웃 구조 |
| 이도은 |      프론트       |- 서비스 초안(Figma) 및 ui 선정 작업<br />- app (클라이언트 측 api 모듈, 페이지 이동) 및  index 세팅<br />- 인증, 회원 관련 페이지 및 기능 구현<br />- 루트 페이지 및 기타 서브 페이지 스타일 작업 및 버튼 기능 구현<br />- 헤더 component 기능 및 유저 프로필 기능 구현 <br />- Kakao 로그인 user의 이메일 추가 등록 및 modal 기능 구현|
| 조대찬 |     백엔드 리드     |- 시스템 아키텍쳐 및 배포<br />- 서버 아키텍쳐<br />- 데이터베이스 아키텍쳐<br />- SSL/TLS<br />- 회원, 인증/인가 관련 API 구현<br />- 학습 API 구현<br />- 학습 진행률 API 구현<br />- 단어장 관련 API 구현<br />- 단어 검색 API 구현<br />- 리마인드 스케쥴러 구현<br />- jest TDD<br />- load test|


<br />
<br />

## **기술 스택**

### Front

![React](https://img.shields.io/badge/-React-222222?style=for-the-badge&logo=react)
![Typescirpt](https://img.shields.io/badge/-Typescirpt-3178C6?style=for-the-badge&logo=Typescript&logoColor=ffffff)

### Server

![Node.js](https://img.shields.io/badge/-Node.js-339933?style=for-the-badge&logo=node.js&logoColor=white)
![Express](https://img.shields.io/badge/-Express-000000?style=for-the-badge&logo=express&logoColor=white)
![Typescirpt](https://img.shields.io/badge/-Typescirpt-3178C6?style=for-the-badge&logo=Typescript&logoColor=ffffff)
![MySQL](https://img.shields.io/badge/-MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white)
![Prisma](https://img.shields.io/badge/-Prisma-1B222D?style=for-the-badge&logo=prisma&logoColor=white)
![Passport](https://img.shields.io/badge/-Passport-34E27A?style=for-the-badge&logo=passport&logoColor=white)
![JWT](https://img.shields.io/badge/-JWT-000000?style=for-the-badge&logo=jsonwebtokens&logoColor=white)
![Nodemailer](https://img.shields.io/badge/-Nodemailer-339933?style=for-the-badge&logo=nodemailer&logoColor=white)
![Multer](https://img.shields.io/badge/-Multer-FF6600?style=for-the-badge&logo=multer&logoColor=white)
![Joi](https://img.shields.io/badge/-Joi-F47920?style=for-the-badge&logo=Joi&logoColor=white)
![Morgan](https://img.shields.io/badge/-Morgan-000000?style=for-the-badge&logo=morgan&logoColor=white)
![Winston](https://img.shields.io/badge/-Winston-231F20?style=for-the-badge&logo=Winston&logoColor=white)
![Jest](https://img.shields.io/badge/-Jest-C21325?style=for-the-badge&logo=Jest&logoColor=white)

### AI Server
![python](https://img.shields.io/badge/-python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![fastapi](https://img.shields.io/badge/-fastapi-009688?style=for-the-badge&logo=fastapi&logoColor=white)
![langchain](https://img.shields.io/badge/-langchain-121D33?style=for-the-badge&logo=langchain&logoColor=white)
![gunicorn](https://img.shields.io/badge/-qunicorn-499848?style=for-the-badge&logo=qunicorn&logoColor=white)
![openai](https://img.shields.io/badge/-openai-412991?style=for-the-badge&logo=openai&logoColor=white)
![pydantic](https://img.shields.io/badge/-pydantic-E92063?style=for-the-badge&logo=pydantic&logoColor=white)

### 배포 및 사용도구

![Ubuntu](https://img.shields.io/badge/-ubuntu-E95420?style=for-the-badge&logo=ubuntu&logoColor=white)
![nginx](https://img.shields.io/badge/-nginx-009639?style=for-the-badge&logo=nginx&logoColor=white)
![docker](https://img.shields.io/badge/-docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![swagger](https://img.shields.io/badge/-swagger-85EA2D?style=for-the-badge&logo=swagger&logoColor=white)
![discord](https://img.shields.io/badge/-discord-5865F2?style=for-the-badge&logo=discord&logoColor=white)
![Figma](https://img.shields.io/badge/-Figma-A259FF?style=for-the-badge&logo=figma&logoColor=white)
![GitLab](https://img.shields.io/badge/-GitLab-FCA121?style=for-the-badge&logo=gitlab&logoColor=white)

<br />
<br />

## **서비스 아키텍쳐**
![wordy-learn-logic](https://github.com/daechan-jo/Wordy/assets/103374153/b11152c3-e825-4538-9994-ff54cb5ce11a)

<br />
<br />

## **ERD**
![word ERD](https://github.com/daechan-jo/Wordy/assets/103374153/66bb61cb-c3f8-4e2f-904b-9583d137bf4b)

<br />
<br />


## **서비스 시퀀스 다이어그램**

- 회원 서비스 시퀀스 다이어그램
![git-auth-sequence-diagram drawio](https://github.com/daechan-jo/Wordy/assets/103374153/c4b0abc9-1cc7-43d0-9111-6a6c35553257)

- 학습 서비스 시퀀스 다이어그램
![wordy-learn-logic drawio](https://github.com/daechan-jo/Wordy/assets/103374153/db6ae998-f99a-417c-a1b9-3863228483cc)

<br />
<br />

<br />

## **주요 기능 및 특징**

### **1. 회원 관리**

서비스는 회원가입 혹은 로그인 후 이용 가능하며, 이메일 인증을 통해 회원가입이 진행됩니다. 소셜 로그인 시 이메일 제공이 없다면, 내 정보에서 이메일을 직접 입력해야 합니다.

### **2. 단어 학습**

단어 학습은 4개의 공인인증시험 카테고리를 통해 이루어지며, 사용자는 10개의 단어를 학습하고 테스트합니다. 정답과 오답 결과는 학습 결과 창에서 확인할 수 있습니다. 학습한 단어는 랭킹 시스템의 점수로 변환되며, 사용자는 자신과 다른 유저의 랭킹을 확인할 수 있습니다.

### **3. 문법 교정 [AI]**

문법 교정 기능은 사용자가 작성한 문장을 AI가 교정하여 올바른 영어 문장을 생성해줍니다.

### **4. 단어장 및 저장소**
단어장 및 저장소에서 학습한 단어, 틀린단어, 카테고리별 단어, 즐겨찾기 등 단어들을 한눈에 확인하고 추가로 커스텀 단어를 등록하거나 즐겨찾기에 등록할 수 있습니다. 또한 검색API를 통해 서비스에 등록된 단어를 검색할 수 있습니다.

### **4. 내 정보 페이지 및 리마인드 서비스**

내 정보 페이지에서 유저의 개인 정보와 학습 진행률을 확인할 수 있으며, 학습현황에 따라 이메일을 통해 리마인드 서비스를 제공합니다.

<br />
<br />





<br />
<br />


## **프로젝트 실행 방법**
### 1. back 루트경로에 dotenv 생성 / 설정
```
DATABASE_URL=
SERVER_URL=
SERVER_PORT=
JWT_SECRET_KEY=
JWT_TOKEN_EXPIRES=
SESSION_SECRET_KEY=

NODE_MAILER_USER=
NODE_MAILER_PASS=

KAKAO_ID=

WORDY_ICON= 리마인드 서비스에 사용할 아이콘(base64)
```

### 2. DB연결 확인 후 프리즈마 스키마 마운트

```npx prisma db push```

### 3. 영단어 데이터셋 마운트 및 사지선다 데이터 생성 (터미널 /back 경로에서)
```npx ts-node src/data/insertWord.ts```

```npx ts-node src/data/insertMeaning.ts```


 </br>

### 4. front 루트경로에 dotenv 생성 / 설정
```
REACT_APP_SERVER_URL=
REACT_APP_SERVER_URL_API=
REACT_APP_GPT_SVR_URL=
REDIRECT_URI=
REACT_APP_GPT_TOKEN=
```



<br />

### 서버 실행
back 루트경로로 이동
- `yarn install`
- `yarn start`


<br />

### 클라이언트 실행
front 루트경로로 이동
- `yarn install`
- `yarn start`


<br />
<br />



## **기능명세서**
[기능명세서.notion](https://www.notion.so/elice/e7c8af41f6b64b53af981bbd0aa6adfc?v=b13d2455ce45444c82ca85cb13ac22fe&pvs=4)




## **버전**

- 0.0.1
