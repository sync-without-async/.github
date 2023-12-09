> [2023-2 한림대학교 소프트웨어캡스톤디자인(02)]
# 비대면 재활치료를 돕는 웹서비스, Re:Hab

2023 Hallym University Capstone Design Project "Re:Hab" Organization Main README.md

## 🏆 Prize 

**2023학년도 2학기 한림대학교 소프트웨어캡스톤디자인 경진대회 대상 (1위, 총장상) 수상 🏆**

<img width="800px" src="https://github.com/sync-without-async/.github/assets/53892427/7148accc-0bac-4dbf-8126-1d80a8bb7f86">


## 🫱🏻‍🫲🏻 Sync-without-Async Team

|FE | FE | BE | BE | AI |
| :---: | :---: | :---: | :---: | :---: |
|  <img width="130px" src="https://avatars.githubusercontent.com/u/53892427?v=4" /> |  <img width="130px" src="https://avatars.githubusercontent.com/u/35104213?v=4" /> |   <img width="130px" src="https://avatars.githubusercontent.com/u/80760160?v=4" /> | <img width="130px" src="https://avatars.githubusercontent.com/u/52206904?v=4"/> |   <img width="130px" src="https://avatars.githubusercontent.com/u/17959335?v=4" /> |
| 오소현 | 김경재 | 이동헌 | 박주영 | 박인성 |
|한림대학교|한림대학교|한림대학교|한림대학교|한림대학교|
|빅데이터전공 4학년|빅데이터전공 2학년 |빅데이터전공 4학년| 콘텐츠IT전공 3학년 | AI의료융합전공 2학년 |
|   [@osohyun0224](https://github.com/osohyun0224)   |  [@PortalCube](https://github.com/PortalCube)  |   [@Dong Heon Lee](https://github.com/Sirius506775)   |   [@JuYoung Park](https://github.com/jyp-on)   |[@InSung Bahk](https://github.com/insung3511) |

## 🛠️ Re:Hab Tech Stacks

| 🫱🏻‍🫲🏻  Sync-without-Async Team | 📚 Tech Stacks  |
|:---:|:---:|
| Collaboration Tools|``Github`` ``Slack`` ``Notion``|

## [FrontEnd Repo](https://github.com/sync-without-async/Rehab-FrontEnd)
|🧑🏻‍💻  FrontEnd  Team | 📚 Tech Stacks  |
|:---:|:---:|
|Dev Packages |``React`` ``Redux`` ``Axios`` |
|Development Support Tools  |``ESLint`` ``Prettier``  ``Vercel`` ``Vite``|

## [BackEnd Repo](https://github.com/sync-without-async/Rehab-BackEnd)

|🧑🏻‍💻  BackEnd  Team | 📚 Tech Stacks  |
|:---:|:---:|
| Environment | `InteliJ` `Postman` `Git Action` `Git` `Gradle` `Raspberry Pi 4B` `AWS` |
| Development | `Spring-Boot` `Java` `NCP(Naver Cloud Platform)` `MariaDB` `WebSocket` |
| Dependencies | `mariadb-java-client` `gson` `query-dsl` `spring data jpa` `spring security` `jwt` `lombok` `jcodec` `aws-java-sdk` `thumbnailator` `spring boot starter` |

## [AI ML Repo](https://github.com/sync-without-async/Rehab-ML) / [AI Audio Repo](https://github.com/sync-without-async/Rehab-Audio)

|🧑🏻‍💻  AI Team | 📚 Tech Stacks  |
|:---:|:---:|
| Frameworks Server | `FastAPI` `uvicorn` `mysql` `pymysql` |
| Frameworks AI | `Pytorch` `Numpy` `torch` `torchaudio` `ultralytics` `transformers` |
| Frameworks Pre-processing | `Scikit-learn` `Scikit-video` `OpenCV` `denoiser` |
| Environment | `Macbook Pro M1` `GTX 2070 Super` `Visual Studio Code` `Postman` |

-----

## 1. 프로젝트 명
비대면 재활 치료를 돕는 웹 서비스, Re:Hab

![image](https://github.com/osohyun0224/Capstone-Rehab-FrontEnd/assets/53892427/cfae25b7-cfd3-42da-a0ce-f902d15d43c8)

## 2. 프로젝트 소개
> 본 프로젝트는 병원을 도메인으로 하는 비대면 재활치료를 돕는 웹서비스이다.

> 전문의는 외래 진료시 환자 차트 작성하고, 재활 운동사에게 해당 환자에 대한 정보와 재활 운동 요청서를 작성한다. 재활치료사는 전문의의 재활 요청서를 바탕으로 해당 환자에게 맞는 과제를 할당해준다. 이와 같은 통합적인 EMR 기능을 제공한다.

> 환자는 본 웹사이트에서 재활 운동 강의를 수강해 재활 치료를 진행한다. 환자가 운동을 수강하면 AI는 유사도를 판정해 유사도를 반환해준다. 80%이상의 유사도를 받아야 합격으로, 다음 강의를 수강할 수 있다. 이는 환자가 올바른 자세로 운동을 수강할 수 있도록 효율적인 재활치료를 돕는다.

> 환자는 또한 본인의 담당 의료진에게 비대면 진료를 요청할 수 있고, 비대면 진료 내용을 AI가 요약해줘 요약본을 환자의 상세 차트에 기록해 추후 의료진이 환자를 진찰하는데 도움을 준다.

## 3. 프로젝트 Workflows
![image](https://github.com/osohyun0224/Capstone-Rehab-FrontEnd/assets/53892427/12a90f49-06ee-4281-a188-97bbc696b211)

## 4. 프로젝트 기획 의도
![image](https://github.com/osohyun0224/Capstone-Rehab-FrontEnd/assets/53892427/8144c422-3f15-4c35-a8b8-470c69555d2d)

## 5. 프로젝트 기능 소개
![image](https://github.com/osohyun0224/Capstone-Rehab-FrontEnd/assets/53892427/666192f1-f365-490b-9077-4661d5e120f3)

![image](https://github.com/osohyun0224/Capstone-Rehab-FrontEnd/assets/53892427/83f60c2f-c338-411b-b747-49e9c21f7c6a)

![image](https://github.com/osohyun0224/Capstone-Rehab-FrontEnd/assets/53892427/55aef1d6-acfc-410d-9b39-292b48d44dfb)

![image](https://github.com/osohyun0224/Capstone-Rehab-FrontEnd/assets/53892427/5b1aafba-0e3b-42be-aff1-2f5eecc7e320)

![image](https://github.com/osohyun0224/Capstone-Rehab-FrontEnd/assets/53892427/fa52a4c5-38cf-49b4-b38c-1715a51ada79)


## 6. 프로젝트 시연 영상

[시연영상 바로가기](https://youtu.be/HuXwZLn8_XQ)

## 7. 프로젝트 전체 아키텍쳐

![image](https://github.com/osohyun0224/Capstone-Rehab-FrontEnd/assets/53892427/3443a38d-a517-4b8d-9429-e5812d70bb4a)
