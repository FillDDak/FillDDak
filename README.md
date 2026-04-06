<!-- 헤더 -->
<div align="center">

# 안녕하세요, 최현규입니다 👋

**작은 것까지 직접 챙기는 풀스택 개발자입니다.**

[![GitHub](https://img.shields.io/badge/GitHub-FillDDak-181717?style=flat-square&logo=github)](https://github.com/FillDDak)
[![Email](https://img.shields.io/badge/Email-cgr456@naver.com-EA4335?style=flat-square&logo=gmail&logoColor=white)](mailto:cgr456@naver.com)

</div>

---

## About Me

실제 클라이언트의 요구사항을 분석하고 직접 배포까지 경험한 1인 풀스택 프로젝트부터, 6인 팀 프로젝트까지 다양한 방식으로 개발해왔습니다. <br>
최근에는 **AI API를 실제 서비스에 녹여내는 것**에 관심을 갖고 있고, 기능 구현뿐 아니라 보안과 인프라까지 직접 챙기는 편입니다.

- 🌐 실제 서비스 운영 경험 있음 — [przo.kr](https://przo.kr)
- 🤖 GPT-4, GPT-3.5, face-api.js 등 AI 기술을 프로젝트에 직접 적용
- 🔐 Spring Security, JWT, Rate Limiting, BCrypt 등 보안 구현 경험
- ☁️ Oracle Cloud 기반 서버 구축 및 배포 경험 (Nginx, Let's Encrypt)

---

## Tech Stack

**Backend**

![Java](https://img.shields.io/badge/Java-007396?style=flat-square&logo=openjdk&logoColor=white)
![Spring Boot](https://img.shields.io/badge/Spring_Boot-6DB33F?style=flat-square&logo=springboot&logoColor=white)
![Spring Security](https://img.shields.io/badge/Spring_Security-6DB33F?style=flat-square&logo=springsecurity&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white)
![Express](https://img.shields.io/badge/Express-000000?style=flat-square&logo=express&logoColor=white)

**Frontend**

![React](https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black)
![Vue.js](https://img.shields.io/badge/Vue.js-4FC08D?style=flat-square&logo=vuedotjs&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat-square&logo=css3&logoColor=white)
![Vite](https://img.shields.io/badge/Vite-646CFF?style=flat-square&logo=vite&logoColor=white)

**Database**

![Oracle](https://img.shields.io/badge/Oracle_DB-F80000?style=flat-square&logo=oracle&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white)

**Infra & Tools**

![Oracle Cloud](https://img.shields.io/badge/Oracle_Cloud-F80000?style=flat-square&logo=oracle&logoColor=white)
![Nginx](https://img.shields.io/badge/Nginx-009639?style=flat-square&logo=nginx&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)
![Figma](https://img.shields.io/badge/Figma-F24E1E?style=flat-square&logo=figma&logoColor=white)

---

## Projects

### 🪲 PRZO — 해충방제 기업 웹사이트 `실서비스 운영 중`

> 실제 클라이언트 수주 프로젝트. 요구사항 수집부터 설계, 개발, 배포까지 1인 풀스택으로 진행했습니다.

**2026.02 ~ 2026.03** | Java 17 · Spring Boot 3.5 · React 18 · Oracle Cloud

회사 소개, 상담 문의, 관리자 페이지를 포함한 기업 웹사이트입니다. <br>
문의 비밀번호 BCrypt 해싱, HttpOnly 쿠키 기반 인증, IP Rate Limiting, Cloudflare Turnstile CAPTCHA, 개인정보 자동 삭제 스케줄러 등 보안에 특히 신경을 썼습니다. <br>
관리자 기능으로 견적서 공유 링크 발급, FAQ 및 시공 사진 관리, 로그인 시도 기록 조회까지 구현했습니다.

🔗 [배포 링크](https://przo.kr) · [GitHub](https://github.com/FillDDak/przo)

---

### 🗂️ PortFlux — 포트폴리오 마켓플레이스 + 채용 플랫폼

> 개발자들이 취업·이직 과정에서 서로의 포트폴리오를 사고팔 수 있는 SNS형 플랫폼입니다.

**2025.11 ~ 2026.01** | Java 17 · Spring Boot 3.5 · React 18 · Oracle DB 18c | 팀 프로젝트 (6인)

포트폴리오 PDF 업로드 및 미리보기, 아임포트 결제 연동 (카드·카카오페이), JWT 인증, Google OAuth 2.0 로그인, OpenAI 기반 자료 요약, 팔로우/좋아요/댓글 등 SNS 기능을 포함합니다. <br>
저는 **마이페이지 기능 구현**을 담당했습니다.

🔗 [GitHub](https://github.com/FillDDak/PortFlux)

---

### 🎤 When Ur Ready — AI 면접 준비 플랫폼

> 구직자가 지원 기업의 채용공고 링크를 입력하면, AI가 키워드를 추출해 예상 면접 질문을 자동 생성해주는 서비스입니다.

Vue.js · Node.js · Express · MySQL | AI 기반 면접 질문 생성 및 피드백

회사 홈페이지 크롤링 → 키워드 추출 → 면접 질문 생성 → 사용자 답변 AI 피드백의 흐름을 구현했습니다. <br>
자기소개서 AI 검토, face-api.js를 활용한 **면접 표정 실시간 분석**, 스터디 그룹 모집 게시판, 즐겨찾기 기능도 포함합니다.

🔗 [GitHub](https://github.com/FillDDak/when_ur_ready)

---

### 📋 Contract Checker — AI 근로계약서 검토 서비스

> 근로계약서 이미지를 업로드하면 AI가 필수 항목 누락 여부를 자동으로 검토해주는 서비스입니다.

Vue.js · Node.js · Express · Tesseract.js · GPT-4

Tesseract.js OCR로 계약서 이미지에서 텍스트를 추출한 뒤, GPT-4가 근로 계약 기간·임금·근무 장소 등 8개 필수 항목의 포함 여부를 검토합니다. <br>
항목별 결과를 시각적으로 보여줍니다.

🔗 [GitHub](https://github.com/FillDDak/contract_checker)

---

### 🏋️ H-Calendar — AI 운동 추천 캘린더

> 일상과 운동 기록을 캘린더에 남기고, 개인 신체 정보를 입력하면 AI가 맞춤 운동을 추천해주는 앱입니다.

Vue.js · Node.js · Express · MySQL · OpenAI API | 소프트웨어 공학 수업 팀 프로젝트

날짜별 기록 작성/삭제, 나이·성별·체중·키·체력 수준·운동 목표를 입력하면 GPT가 맞춤 운동 루틴을 추천해줍니다.

🔗 [GitHub](https://github.com/FillDDak/H-Calendar)

---

<div align="center">

[![Activity Graph](https://github-readme-activity-graph.vercel.app/graph?username=FillDDak&hide_border=true&area=true&theme=github-compact)](https://github.com/FillDDak)

![Profile Summary](https://github-profile-summary-cards.vercel.app/api/cards/profile-details?username=FillDDak&theme=default)

![Top Languages by Commit](https://github-profile-summary-cards.vercel.app/api/cards/most-commit-language?username=FillDDak&theme=default)

![Top Languages by Repo](https://github-profile-summary-cards.vercel.app/api/cards/repos-per-language?username=FillDDak&theme=default)

![Productive Time](https://github-profile-summary-cards.vercel.app/api/cards/productive-time?username=FillDDak&theme=default&utcOffset=9)

![Profile Views](https://komarev.com/ghpvc/?username=FillDDak&style=flat-square&color=blue&label=조회수)

</div>

---

<div align="center">

<sub>📬 cgr456@naver.com</sub>

</div>
