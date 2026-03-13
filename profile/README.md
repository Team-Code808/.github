<h1 align="center"><img width="200" height="200" alt="Image" src="https://github.com/user-attachments/assets/864e2587-d2ab-4305-a134-8c71b75cd511" /></h1>
<h1 align="center">CalmDesk (칼름데스크) </h1>

<h4 align="center">
**CalmDesk**는 콜센터 상담 인력이 겪는 감정 노동과 정신적 부담을 체계적으로 관리하고 보호하기 위한 HR·건강 통합 관리 시스템입니다. <br>
상담 중 발생하는 스트레스와 악성 민원 노출을 정량적으로 분석하여 상담원을 보호할 수 있는 실질적인 관리 체계를 제공합니다.
</h4>

---

<br>
<br>

## 📘 개발 목표 (Development Goals)
### 1️⃣ 상담원 정서 보호 

🔹 AI를 활용해 콜센터 상담원의 스트레스 상태를 분석하고 관리하는 시스템을 구축하여, 고위험군 발생 시 상담 매칭 및 강제 휴식(Cooldown)을 통해 번아웃을 예방.

### 2️⃣ 데이터 기반 조직 관리 

🔹 근태 정보와 스트레스 데이터를 연동해 직원의 건강 상태까지 고려한 스마트 관리 환경을 제공하고, 통합 대시보드를 통해 조직 상태를 직관적으로 파악할 수 있도록 지원.

### 3️⃣ 멀티테넌시 기반 확장성

🔹 기업별 데이터가 완전히 분리되도록 멀티테넌시 구조를 설계하여 여러 기업이 독립적으로 사용할 수 있는 확장 가능한 구독형 서비스 환경을 제공.

### 4️⃣ 실시간 소통 및 참여 유도 

🔹 WebSocket과 SSE를 활용한 실시간 알림 및 채팅 기능과 포인트·기프티콘 보상 체계를 통해 직원 참여와 서비스 몰입도를 높임.

<br>
<br>


# 🌟 사용자 역할별 주요 기능

## 💼 관리자 페이지 (Admin)
> 기업의 자원을 효율적으로 운영하고 조직원의 정서적 건강을 관리합니다.


### 🖼️ 헤더 네비게이션
- 통합현황: 전사 스트레스 지수 및 부서별 업무 현황 요약.
  
- 팀원관리: 전 사원의 개인 정보, 직급 및 권한 설정 관리.
  
- 상세분석: 심층적인 필터링을 통한 월간/분기별 정서 지표 분석.
  
- 신청관리: 휴가, 연차, 상담 등 모든 결재 요청 건에 대한 승인/반려 처리.
  
- 기프티콘 관리: 복지 몰 상품 등록 및 발급 내역 관리.

- 마이페이지: 개인정보 수정 및 비밀번호 관리.


### 🔔 관리자 전용 알림 및 소통
- 운영 알림 센터: 신규 팀원 가입 요청, 긴급 상담 신청 등을 실시간으로 감지하여 알림 제공.
- 통합 채팅 관리: 직원들의 상담 요청에 대한 실시간 응대 및 이력 관리.

<br>

## 🧑 직원 페이지 (Employee)
> 업무 생산성 향상과 정서적 케어를 위한 개인 특화 기능을 제공합니다.

### 🖼️ 헤더 네비게이션 
- 대시보드: 개인 업무 통계 및 정서 지수 요약 정보 확인.
  
- 부서정보: 소속 부서의 팀원 명단 및 조직도 확인.
  
- 근태관리: 실시간 출퇴근 체크 및 연차 사용 내역 관리.
  
- 상담신청: 전문 상담사와의 실시간 상담 예약 및 내역 확인.
  
- 통화기록: AI가 요약한 본인의 통화 녹취록 및 감정 분석 결과 조회.
  
- 포인트몰: 적립된 성과 포인트로 기프티콘 등 복지 상품 구매.

- 마이페이지: 개인 프로필 관리 , 기프티콘 보관함 , 포인트 및 결제 내역 관리.


### 💬 실시간 소통 및 알림
- 실시간 챗봇: AI 비서 기능을 통해 업무 관련 질문에 즉각적인 답변 제공.
- 그룹 채팅: N:N 또는 1:1 채팅을 통한 실시간 정서 케어 및 업무 지원.
- 스마트 알림 센터: SSE기술을 활용하여 휴가 승인, 공지사항 등을 실시간 푸시 알림으로 수신.

---

<br>

## 🛠 기술 스택
| 분류 | 구분 | 기술 상세 |
| :--- | :--- | :--- |
| Backend | 프레임워크 / 언어 | Spring Boot , Java 17 |
| | 데이터베이스 / 캐시 | MySQL , Redis , JPA  |
| | AI 지능형 서비스 | Spring AI (OpenAI, Ollama, Google GenAI), Google Cloud STT API |
| | 보안 / 인터페이스 | Spring Security, JWT , WebSocket , Swagger |

| 분류 | 구분 | 기술 상세 |
| :--- | :--- | :--- |
| Frontend | 프레임워크 / 언어 | React , JavaScript |
| | 상태 / 스타일링 | Zustand , Styled-components, Vanilla CSS |
| | 데이터 시각화 | Recharts , Lucide React |
| | 통신 라이브러리 | Axios, StompJS |
| | 소통 | Slack, Notion, 카카오톡 |


---

<br><br>

# 🎬 시연 화면 (Demonstration)

| 직원으로 로그인 후 헤더를 통한 페이지 이동 | 관리자로 로그인 후 헤더를 통한 페이지 이동 |
|:---:|:---:|
| <img src="https://github.com/user-attachments/assets/f601965e-97cf-4be7-bdef-049674fc05f2" width="600" />  | <img src="https://github.com/user-attachments/assets/ce1e75c6-7451-42ba-a57f-3f81fdf18ef5" width="600" /> |

| 관리자로 인한 실시간 포인트몰 관리  | 직원의 출근버튼 입력시 미션 진행/완료 | 직원이 근태신청시 관리자에게 승인받기  |
|:---:|:---:|:---:|
| <img src="https://github.com/user-attachments/assets/87d8550a-2f09-4c05-94e9-680982779d6b" width="500" /> | <img src="https://github.com/user-attachments/assets/385850a7-0cde-46bb-947a-62b6edfb47ae" width="500" /> | <img src="https://github.com/user-attachments/assets/1655abb1-23d6-4762-834e-07c4e27a3fe3" width="400" /> |


| 출근 , 미션 , 상담신청 완료시 알림전송 | 타 직원간의 대화방을 만들어 실시간 채팅 | 욕설 녹음 |
|:---:|:---:|:---:|
| <img src="https://github.com/user-attachments/assets/be866c00-0ba7-4a15-8126-f6d543964415" width="550" /> | <img src="https://github.com/user-attachments/assets/1ec45021-c2eb-4c1f-bc6f-521efde69794" width="550" /> | <img src="https://via.placeholder.com/400x225.png?text=Point+Mall" width="550" /> |

---

<br><br>

## 📂 프로젝트 구조 (Project Structure)


<br/>

> ### ![Backend](https://img.shields.io/badge/Backend-4A90E2?style=for-the-badge&logo=spring&logoColor=white) 
>
> <details>
> <summary><b>📂 Backend 상세 폴더 구조 보기 (Click to expand)</b></summary>
>
> <pre>
> ├── src/main/java/com/code808/calmdesk/
> │   ├── domain/             # 핵심 비즈니스 로직
> │   │   ├── ai/             # AI 서비스 통합
> │   │   ├── attendance/     # 근태 및 연차 관리
> │   │   ├── auth/           # 로그인 및 권한 인증
> │   │   ├── businesscard/   # 명함 관리
> │   │   ├── callrecord/     # STT 및 감정 분석
> │   │   ├── chat/           # 실시간 채팅 모듈
> │   │   ├── company/        # 회사 및 조직 관리
> │   │   ├── consultation/   # 심리 상담 신청
> │   │   ├── dashboard/      # 데이터 시각화
> │   │   ├── gifticon/       # 복지 포인트 몰
> │   │   ├── member/         # 사용자 정보 관리
> │   │   ├── monitoring/     # 실시간 상태 모니터링
> │   │   ├── mypage/         # 개인 설정
> │   │   ├── Notification/   # 실시간 알림
> │   │   ├── team/           # 팀 구성 관리
> │   │   └── vacation/       # 휴가 결재 시스템
> │   └── global/             # 공통 설정 및 보안
> │       ├── config/         # App/Security 설정
> │       ├── dto/            # 공통 DTO
> │       ├── exception/      # 예외 처리
> │       └── security/       # JWT 설정
> ├── src/main/resources/     # 환경 설정 및 SQL
> ├── build.gradle            # 빌드 및 의존성 관리
> └── docs/                   # 설계 및 가이드 문서
> </pre>
>
> </details>
>
> <br/>
>
> ### ![Frontend](https://img.shields.io/badge/Frontend-50E3C2?style=for-the-badge&logo=react&logoColor=white) 
>
> <details>
> <summary><b>📂 Frontend 상세 폴더 구조 보기 (Click to expand)</b></summary>
> <pre>
>    ├── src/
>        ├── components/         # 재사용 UI 컴포넌트
>        ├── pages/              # 라우팅 페이지 구성
>        ├── store/              # Zustand 전역 상태 관리
>        ├── api/                # API 통신 설정
>        ├── assets/             # 이미지 및 스타일 자원
>        ├── hooks/              # 커스텀 React 훅
>        └── utils/              # 공용 유틸리티 함수
> </pre>
> </details>


<br/>

---



<br>


## 🚀 시작하기

### Backend 설정
1. Java 17 및 MySQL 설치 확인
2. `Backend/src/main/resources/application-secret.yaml` 작성 (API 키 등 민감 정보)
3. 빌드 및 실행:
   ```bash
   cd Backend
   ./gradlew bootRun
   ```

### Frontend 설정
1. Node.js 설치 확인
2. 의존성 설치 및 실행:
   ```bash
   cd Frontend
   npm install
   npm run dev
   ```

<br><br>

## 🏆 최종 프로젝트 PPT 🏆 ##

<a href="https://www.canva.com/design/DAHCTmWQkM0/V_8KTiPn3yDTZkF9QKyhqg/view?utm_content=DAHCTmWQkM0&utm_campaign=designshare&utm_medium=link2&utm_source=uniquelinks&utlId=h3e6c73b7bf" 
   style="font-size: 24px;         /* 글씨 크기 확대 */
          color: #DC3545;          /* 강렬한 빨간색 */
          font-weight: 900;        /* 폰트 굵기를 최대로 */
          text-decoration: underline;"> 🔥 CalmDesk 최종 프로젝트 보고서 🔥
</a>

<br><br>


## 🤝 프로젝트 팀 구성 및 역할 분담

| 이름 | 포지션 | 담당 역할 | GitHub / Contact |
| :---: | :---: | :---: | :--- |
| 👑 **박준언** | **조장 (Team Lead)** | 프로젝트 총괄 및 의사 결정 | **[GitHub: 박준언](https://github.com/junown)** |
| ⚙️ **백승원** | **형상 관리자** | Git 브랜치 전략 및 버전 관리 | **[메일: 백승원](paiktmddnjs@naver.com)** |
| 🗄️ **김정훈** | **DB 관리자** | 데이터베이스 설계 및 초기 구축 | **[GitHub: 김정훈](https://github.com/kimsesdook)** |
| 🗓️ **장원석** | **일정 관리자** | Sprint 및 마일스톤 관리 | **[GitHub: 장원석](https://github.com/1suk)** |
| 🐞 **조치호** | **이슈 관리자** | 이슈 트래킹 및 피드백 통합 관리 | **[GitHub: 조치호](https://github.com/xxh3898)** |

