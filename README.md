<div align="center">

![header](https://capsule-render.vercel.app/api?type=waving&color=0:0F766E,50:16A34A,100:84CC16&height=210&section=header&text=SUHYUN%20OH&fontSize=48&fontColor=ffffff&fontAlignY=36&desc=Backend%20Developer%20%C2%B7%20Service%20Builder&descSize=18&descAlignY=57)

### 기능을 실제 서비스로 연결하는 백엔드 개발자 오수현입니다.

요구사항을 코드로 옮기는 것에서 끝내지 않고<br>
**데이터베이스 · 테스트 · 배포 · 문서화**까지 완성하는 과정을 중요하게 생각합니다.

[![GitHub](https://img.shields.io/badge/GitHub-SsuhyunO-181717?style=for-the-badge&logo=github)](https://github.com/SsuhyunO)

</div>

---

## 👋 About Me

| | |
|---|---|
| **전공** | 부경대학교 컴퓨터공학 |
| **관심 분야** | Java·Spring 기반 백엔드, 데이터 모델링, 서비스 운영 |
| **개발 방향** | 기능 구현부터 배포와 문서화까지 책임지는 개발자 |
| **강점** | 기존 기능의 문제를 추적하고 실제 동작 가능한 형태로 개선 |
| **현재 목표** | 사용자 흐름과 운영 환경을 함께 고려하는 백엔드 개발자로 성장 |

컴퓨터공학 전공 졸업 후 Java·Spring 기반 AI 웹 서비스 과정을 이수하며 웹 서비스 개발과 배포 역량을 집중적으로 보완했습니다. 팀 프로젝트를 통해 요구사항 분석, 데이터베이스 설계, AI 기능 연동 및 Git 기반 협업을 경험했습니다.

---

## 🧰 Tech Stack

<div align="center">

### Backend

![Java](https://img.shields.io/badge/Java-007396?style=flat-square&logo=openjdk&logoColor=white)
![Spring Boot](https://img.shields.io/badge/Spring_Boot-6DB33F?style=flat-square&logo=springboot&logoColor=white)
![Spring Security](https://img.shields.io/badge/Spring_Security-6DB33F?style=flat-square&logo=springsecurity&logoColor=white)
![JPA](https://img.shields.io/badge/JPA-59666C?style=flat-square)

### Database & Infrastructure

![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat-square&logo=amazonwebservices&logoColor=white)
![Nginx](https://img.shields.io/badge/Nginx-009639?style=flat-square&logo=nginx&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white)

### Frontend · AI · Data

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat-square&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![OpenAI](https://img.shields.io/badge/OpenAI-412991?style=flat-square&logo=openai&logoColor=white)

</div>

---

## 🚀 Featured Projects

| Project | Description | Focus |
|:---:|---|---|
| **[K-Market](https://github.com/SsuhyunO/K-Market)** | 일반회원·판매회원·관리자 기능을 분리한 종합 쇼핑몰 | 서비스 개선 · 배포 · 운영 |
| **[First-day](https://github.com/SsuhyunO/First-day-project)** | 구직자와 기업을 연결하는 AI 기반 채용 플랫폼 | Java Spring · AI · 협업 |
| **[GA-TA-ESN](https://github.com/SsuhyunO/GA-TA-ESN-Model)** | 기술적 지표와 ESN을 결합한 매매 신호 예측 모델 | 알고리즘 · 실험 · 재현성 |

<details open>
<summary><b>🛒 K-Market — E-commerce Platform</b></summary>

<br>

일반회원·판매회원·관리자의 이용 흐름을 운영 환경까지 연결한 쇼핑몰 프로젝트입니다.

`Java 21` `Spring Boot` `Spring Security` `JPA` `MySQL` `Thymeleaf` `JavaScript`

- **문제:** 쿠폰 생성 이후 사용자 지급 흐름이 없고, 운영 환경에서 이미지와 관리자 설정이 정상 동작하지 않았습니다.
- **해결:** 회원가입·첫 구매 조건에 따른 쿠폰 발급과 알림을 연결하고, 파일 경로·관리자 설정·화면 오류를 점검했습니다.
- **결과:** 상품·주문·배송·쿠폰·CS 흐름을 실제 사용자가 체험할 수 있도록 정리했습니다.
- **운영:** Google OAuth, GitHub Actions, AWS Lightsail, Nginx와 서버 MySQL을 구성했습니다.

➡️ **[Repository 바로가기](https://github.com/SsuhyunO/K-Market)**

</details>

<details>
<summary><b>💼 First-day — AI Recruitment Platform</b></summary>

<br>

구직자와 기업을 연결하고 AI 기반 문서 작성과 추천 기능을 제공하는 팀 프로젝트입니다.

`Java` `Spring Boot` `Spring Security` `MySQL` `PostgreSQL` `Spring AI` `OpenAI`

- **담당:** 기업·관리자 채용공고 관리, 공고 검색·상세 조회, 입사지원 및 상태 관리 흐름을 구현했습니다.
- **개선:** 지원 취소·재지원과 상태 이력, 기업별 지원자 관리, 공고 공개 조건을 정리했습니다.
- **AI 연동:** 채용공고 문장 다듬기 기능과 공고 작성 화면의 사용성을 개선했습니다.
- **협업:** Git 브랜치·PR 기반으로 작업하고 MySQL·PostgreSQL ERD와 README를 정리했습니다.
- **공개 방식:** 원본 팀 저장소와 기여 이력을 유지하기 위해 Fork 형태로 공개했습니다.

➡️ **[Repository 바로가기](https://github.com/SsuhyunO/First-day-project)**

</details>

<details>
<summary><b>📈 GA-TA-ESN — Stock Trading Signal Model</b></summary>

<br>

금융 시계열의 노이즈를 줄이고 기술적 지표와 ESN을 결합해 매매 신호를 생성한 4인 캡스톤 프로젝트입니다.

`Python` `pandas` `NumPy` `TA-Lib` `DEAP` `scikit-learn` `Backtesting.py`

- **구조:** CPM 변곡점과 GA로 최적화한 MA·RSI·ROC 신호를 ESN 입력으로 사용했습니다.
- **검증:** Train/Validation/Test 기반 Expanding Window 롤링 포워드 백테스트를 적용했습니다.
- **개선:** pandas 자료형, multiprocessing, 라이브러리 호환성과 실행 재현성 문제를 보완했습니다.
- **결과 공개:** 빠른 검증과 전체 실험을 분리하고 폴드별 결과를 정리하고 있습니다.

➡️ **[Repository 바로가기](https://github.com/SsuhyunO/GA-TA-ESN-Model)**

</details>

---

## 🎓 Education & Growth

### 부경대학교 · 컴퓨터공학

`2020.03 — 2026.02` · **3.91 / 4.5**

- 자료구조, 알고리즘, 데이터베이스, 운영체제 및 소프트웨어 공학 학습
- 캡스톤 프로젝트를 통해 데이터 분석 모델의 구현과 실험 과정 경험

### 그린컴퓨터아카데미 부산

`2026.04 — 2026.09`

**AI UX 전략과 RAG 인프라 기반 지능형 웹 서비스(Java Spring) 양성 과정**

- Java·Spring Boot 기반 웹 애플리케이션 구현
- MySQL을 활용한 데이터 모델링과 서비스 연동
- 사용자 요구사항 분석 및 화면·정보 구조 설계
- OpenAI·Spring AI를 활용한 AI 기능 연동
- Git/GitHub 기반 팀 협업과 프로젝트 문서화

교육 과정에서 백엔드 구현, 프론트엔드 연동, 데이터베이스와 배포 환경까지 서비스의 전체 흐름을 경험했습니다. 이후에도 프로젝트의 기능 오류와 배포 구성을 점검하고 문서를 보완하고 있습니다.

---

## 🌱 Working Principles

```text
01. 기능은 실제 사용자 흐름에서 끝까지 동작해야 합니다.
02. 오류는 증상보다 데이터와 요청의 흐름을 따라가며 찾습니다.
03. 개발 환경과 운영 환경의 차이를 고려해 설정합니다.
04. 결과뿐 아니라 과정, 한계와 재현 방법도 함께 기록합니다.
```

---

## 📌 Portfolio

| Channel | Link |
|---|---|
| GitHub | [github.com/SsuhyunO](https://github.com/SsuhyunO) |

<div align="center">

작은 기능이라도 **실제로 동작하고 설명할 수 있는 결과물**로 완성하겠습니다.

![footer](https://capsule-render.vercel.app/api?type=waving&color=0:0F766E,50:16A34A,100:84CC16&height=120&section=footer)

</div>
