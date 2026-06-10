<div align="center">

<img src="https://capsule-render.vercel.app/api?type=soft&color=0:0F172A,45:1D4ED8,100:38BDF8&height=230&section=header&text=유환빈&fontSize=58&fontColor=FFFFFF&animation=fadeIn&fontAlignY=38&desc=Problem%20Solving%20Backend%20Developer%20%7C%20Spring%20Boot%20%C2%B7%20Kafka%20%C2%B7%20AI%2FRAG&descSize=18&descAlignY=62" />

<br/>

[![Typing SVG](https://readme-typing-svg.demolab.com?font=Fira+Code&size=22&duration=2600&pause=900&color=38BDF8&center=true&vCenter=true&width=900&lines=문제를+끝까지+추적하는+Backend+Developer;Spring+Boot+%7C+Kafka+%7C+AI%2FRAG;기능+구현을+넘어+안정적인+구조로+개선합니다)](https://git.io/typing-svg)

<br/>

### 기능 구현을 넘어, 트랜잭션 · 이벤트 · 실시간 알림 · AI 연동까지 고민합니다.

<p>
  <img src="https://img.shields.io/badge/Java-0F172A?style=for-the-badge&logo=openjdk&logoColor=white"/>
  <img src="https://img.shields.io/badge/Spring Boot-1D4ED8?style=for-the-badge&logo=springboot&logoColor=white"/>
  <img src="https://img.shields.io/badge/MySQL-0369A1?style=for-the-badge&logo=mysql&logoColor=white"/>
  <img src="https://img.shields.io/badge/Kafka-111827?style=for-the-badge&logo=apachekafka&logoColor=white"/>
  <img src="https://img.shields.io/badge/AI%2FRAG-2563EB?style=for-the-badge"/>
</p>

</div>

<br/>

## 👋 소개 | About Me

안녕하세요. **백엔드 개발자 유환빈**입니다.

Spring Boot 기반 백엔드 개발을 중심으로  
**인증/권한, 트랜잭션, 동시성 제어, Kafka 이벤트 처리, 실시간 알림, LLM API 연동**을 구현한 경험이 있습니다.



<br/>

## 🧭 핵심 역량 | Core Strength

| 영역 | 어필 포인트 | 대표 경험 |
| --- | --- | --- |
| 백엔드 구조 설계 | Controller-Service-Repository 계층 분리, 책임 분리, 유지보수 가능한 API 설계 | Spring Boot 프로젝트 다수 구현 |
| 데이터 정합성 | 트랜잭션 경계, 상태 전이, 중복 처리, 재시도 구조 고민 | 포인트 구매 / 리뷰 분석 상태 처리 |
| 이벤트 기반 처리 | Kafka Producer/Consumer, Outbox Pattern, 비동기 이벤트 전달 | CafeOrderSystem |
| 실시간 기능 | WebSocket/STOMP 채팅, Firebase FCM 푸시 알림 | checkmate |
| AI 연동 | Spring Boot ↔ AI 서버 연동, 리뷰 감정 분석, RAG 답글 구조 | CafeOrderSystem |
| 문제 해결 | 오류 원인 추적, 구조 개선, 구현 이후 안정성 보완 | AOP 인증 공통화 / Kafka 연결 / 트랜잭션 분리 |

<br/>

## 🚀 대표 프로젝트 | Featured Projects

<table>
  <tr>
    <td width="33%" valign="top">
      <h3>☕ Cafe Review AI System</h3>
      <p>
        <b>Kafka + Outbox + AI 리뷰 분석을 적용한 카페 주문·리뷰·사장 대시보드 시스템</b>
      </p>
      <p>
        주문 이후 QR 리뷰를 수집하고, 구매 서버와 사장 서버를 Kafka 이벤트 기반으로 분리했습니다.
        리뷰는 AI 분석 서버와 연동해 감정 분석, 카테고리 분류, 사장 답글 생성 구조로 확장했습니다.
      </p>
      <p>
        <img src="https://img.shields.io/badge/Spring Boot-6DB33F?style=flat-square&logo=springboot&logoColor=white"/>
        <img src="https://img.shields.io/badge/MyBatis-111827?style=flat-square"/>
        <img src="https://img.shields.io/badge/JPA-59666C?style=flat-square"/>
        <img src="https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white"/>
        <img src="https://img.shields.io/badge/Kafka-231F20?style=flat-square&logo=apachekafka&logoColor=white"/>
        <img src="https://img.shields.io/badge/Spring AI-6DB33F?style=flat-square&logo=spring&logoColor=white"/>
        <img src="https://img.shields.io/badge/AI%2FRAG-2563EB?style=flat-square"/>
      </p>
      <b>핵심 구현</b>
      <ul>
        <li>구매 서버 / 사장 서버 분리</li>
        <li>QR 기반 리뷰 작성 플로우</li>
        <li>리뷰 저장 + Outbox 이벤트 저장</li>
        <li>Kafka Relay 기반 이벤트 발행</li>
        <li>리뷰 분석 상태 관리</li>
        <li>Spring AI 기반 감정 분석</li>
        <li>RAG 기반 사장 답글 구조 설계</li>
      </ul>
      <p>
        🔗 <a href="https://github.com/haarooo/CafeOrderSystem">구매 서버 Repository</a><br/>
        🔗 <a href="https://github.com/bbrrrvsg/CafeAutoSystem">사장 서버 Repository</a>
      </p>
    </td>
    <td width="33%" valign="top">
      <h3>🏛 우리동네 국회의원</h3>
      <p>
        <b>지역 주민과 국회의원을 연결하는 정치 참여 플랫폼</b>
      </p>
      <p>
        시민이 내 지역구 국회의원을 찾고, 의견을 남기며,
        관련 법안과 뉴스 정보를 함께 확인할 수 있는 지역 기반 정치 참여 서비스입니다.
      </p>
      <p>
        <img src="https://img.shields.io/badge/Spring Boot-6DB33F?style=flat-square&logo=springboot&logoColor=white"/>
        <img src="https://img.shields.io/badge/JPA-59666C?style=flat-square"/>
        <img src="https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white"/>
        <img src="https://img.shields.io/badge/JWT-000000?style=flat-square&logo=jsonwebtokens&logoColor=white"/>
        <img src="https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=111827"/>
        <img src="https://img.shields.io/badge/FCM-FFCA28?style=flat-square&logo=firebase&logoColor=111827"/>
      </p>
      <b>담당 역할</b>
      <ul>
        <li>회원가입 / 로그인</li>
        <li>JWT 기반 인증/권한 처리</li>
        <li>지역 주민 커뮤니티 CRUD</li>
        <li>마이페이지 기능</li>
        <li>관리자 페이지 기능</li>
        <li>AOP 기반 인증 공통화</li>
        <li>포인트 구매 동시성 제어</li>
      </ul>
      <p>
        🔗 <a href="https://github.com/jisung-louis/ourassembly">Repository</a>
      </p>
    </td>
    <td width="33%" valign="top">
      <h3>⚡ CheckMate</h3>
      <p>
        <b>AI-assisted rapid development로 구현한 실시간 미션 인증 앱</b>
      </p>
      <p>
        친구들과 목표를 함께 실천하고, 인증 제출·멤버 확인·실시간 채팅·푸시 알림·포인트 정산까지
        하나의 흐름으로 연결한 팀 미션 인증 서비스입니다.
      </p>
      <p>
        <img src="https://img.shields.io/badge/AI Assisted-2563EB?style=flat-square"/>
        <img src="https://img.shields.io/badge/Spring Boot-6DB33F?style=flat-square&logo=springboot&logoColor=white"/>
        <img src="https://img.shields.io/badge/Flutter-02569B?style=flat-square&logo=flutter&logoColor=white"/>
        <img src="https://img.shields.io/badge/WebSocket-111827?style=flat-square"/>
        <img src="https://img.shields.io/badge/STOMP-0F172A?style=flat-square"/>
        <img src="https://img.shields.io/badge/Firebase FCM-FFCA28?style=flat-square&logo=firebase&logoColor=111827"/>
        <img src="https://img.shields.io/badge/JWT-000000?style=flat-square&logo=jsonwebtokens&logoColor=white"/>
      </p>
      <b>핵심 구현</b>
      <ul>
        <li>AI 도구 기반 빠른 기능 설계/구현</li>
        <li>미션방 생성 / 참여 / 상태 관리</li>
        <li>인증 제출 및 멤버 확인</li>
        <li>WebSocket/STOMP 기반 실시간 채팅</li>
        <li>Firebase FCM 푸시 알림</li>
        <li>포인트 지갑 / 원장 / 정산 흐름</li>
      </ul>
      <p>
        🔗 <a href="https://github.com/haarooo/checkmate">Repository</a>
      </p>
    </td>
  </tr>
</table>

<br/>


## 🛠 기술 스택 | Tech Stack

### Backend

<p>
  <img src="https://img.shields.io/badge/Java 17-007396?style=for-the-badge&logo=openjdk&logoColor=white"/>
  <img src="https://img.shields.io/badge/Spring Boot-6DB33F?style=for-the-badge&logo=springboot&logoColor=white"/>
  <img src="https://img.shields.io/badge/Spring Security-6DB33F?style=for-the-badge&logo=springsecurity&logoColor=white"/>
  <img src="https://img.shields.io/badge/JPA-59666C?style=for-the-badge"/>
  <img src="https://img.shields.io/badge/MyBatis-111827?style=for-the-badge"/>
  <img src="https://img.shields.io/badge/JWT-000000?style=for-the-badge&logo=jsonwebtokens&logoColor=white"/>
</p>

### Database / Message / Realtime

<p>
  <img src="https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white"/>
  <img src="https://img.shields.io/badge/Apache Kafka-231F20?style=for-the-badge&logo=apachekafka&logoColor=white"/>
  <img src="https://img.shields.io/badge/WebSocket-111827?style=for-the-badge"/>
  <img src="https://img.shields.io/badge/STOMP-0F172A?style=for-the-badge"/>
  <img src="https://img.shields.io/badge/Firebase FCM-FFCA28?style=for-the-badge&logo=firebase&logoColor=111827"/>
</p>

### AI / Data

<p>
  <img src="https://img.shields.io/badge/Spring AI-6DB33F?style=for-the-badge&logo=spring&logoColor=white"/>
  <img src="https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white"/>
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white"/>
  <img src="https://img.shields.io/badge/Hugging Face-FFD21E?style=for-the-badge&logo=huggingface&logoColor=111827"/>
  <img src="https://img.shields.io/badge/RAG-2563EB?style=for-the-badge"/>
</p>

### Frontend / Mobile / Tools

<p>
  <img src="https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB"/>
  <img src="https://img.shields.io/badge/Flutter-02569B?style=for-the-badge&logo=flutter&logoColor=white"/>
  <img src="https://img.shields.io/badge/JSP-007396?style=for-the-badge"/>
  <img src="https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white"/>
  <img src="https://img.shields.io/badge/GitHub Actions-2088FF?style=for-the-badge&logo=githubactions&logoColor=white"/>
</p>

<br/>
