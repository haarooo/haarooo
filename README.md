![header](https://capsule-render.vercel.app/api?type=waving&color=0:001830,50:0040A8,100:0878F8&height=230&section=header&text=Hwanbin%20Yoo&fontSize=55&fontColor=ffffff&fontAlignY=38&desc=Backend%20Developer%20%7C%20Spring%20Boot%20%7C%20Kafka%20%7C%20AI%2FRAG&descSize=18&descAlignY=58)

<div align="center">

[![Typing SVG](https://readme-typing-svg.demolab.com?font=Fira+Code&size=23&duration=2600&pause=900&color=0878F8&center=true&vCenter=true&width=850&lines=Backend+Developer;Spring+Boot+%7C+MySQL+%7C+Kafka+%7C+AI%2FRAG;I+build+systems+that+are+reliable%2C+explainable%2C+and+maintainable.)](https://git.io/typing-svg)

</div>

<br/>

## 👋 About Me

안녕하세요.  
**문제를 끝까지 추적하고, 기능 구현을 안정적인 백엔드 구조로 개선하는 개발자 유환빈입니다.**

Spring Boot 기반 백엔드 개발을 중심으로  
인증/권한, 트랜잭션, 동시성 제어, Kafka 이벤트 처리, AI 서버 연동 구조를 학습하고 구현하고 있습니다.

단순히 기능을 만드는 것보다  
**왜 이 구조가 필요한지, 장애 상황에서 어떻게 복구할 수 있는지, 유지보수하기 좋은 코드인지**를 고민합니다.

<br/>

## 🧩 Core Strength

| Area | What I Focus On |
| --- | --- |
| Backend Architecture | Spring Boot 기반 API 설계, 계층 분리, 유지보수 가능한 구조 |
| Data Consistency | 트랜잭션, 동시성 제어, Optimistic Lock, 재시도 구조 |
| Event Driven System | Kafka Producer/Consumer, Outbox Pattern, 서버 간 비동기 연동 |
| AI Integration | FastAPI AI 서버 연동, 리뷰 감정 분석, RAG 기반 자동 답글 구조 |
| Problem Solving | 구현 이후 발생하는 오류를 추적하고 구조적으로 개선 |

<br/>

## 🚀 Featured Projects

<table>
  <tr>
    <td width="33%" valign="top">
      <h3>☕ CafeOrderSystem</h3>
      <p>
        <b>Kafka와 AI 리뷰 분석을 적용한 카페 주문·리뷰·사장 대시보드 시스템</b>
      </p>
      <p>
        POS 주문 이후 QR 리뷰를 수집하고, Kafka 이벤트 기반으로 주문/리뷰 데이터를 전달하며,
        AI 서버를 통해 리뷰 감정 분석과 인사이트 생성을 수행하는 프로젝트입니다.
      </p>
      <p>
        <img src="https://img.shields.io/badge/Spring Boot-6DB33F?style=flat-square&logo=springboot&logoColor=white"/>
        <img src="https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white"/>
        <img src="https://img.shields.io/badge/Kafka-231F20?style=flat-square&logo=apachekafka&logoColor=white"/>
        <img src="https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white"/>
        <img src="https://img.shields.io/badge/AI%2FRAG-0878F8?style=flat-square"/>
      </p>
      <ul>
        <li>구매 서버와 사장 서버 분리</li>
        <li>Kafka 기반 주문/리뷰 이벤트 전달</li>
        <li>QR 리뷰 작성 플로우 구현</li>
        <li>FastAPI AI 서버 연동</li>
        <li>리뷰 감정 분석 및 카테고리 분류</li>
        <li>RAG 기반 사장 답글 생성 구조 설계</li>
      </ul>
      <p>
        🔗 <a href="https://github.com/haarooo/CafeOrderSystem">Repository</a>
      </p>
    </td>
    <td width="33%" valign="top">
      <h3>🏛 ourassembly</h3>
      <p>
        <b>지역 주민과 국회의원을 연결하는 정치 참여 플랫폼</b>
      </p>
      <p>
        지역 주민이 의견을 작성하고 의원 정보를 확인할 수 있는 플랫폼입니다.
        백엔드 담당으로 인증/권한, 게시판, 마이페이지, 관리자, 포인트 기능을 구현했습니다.
      </p>
      <p>
        <img src="https://img.shields.io/badge/Spring Boot-6DB33F?style=flat-square&logo=springboot&logoColor=white"/>
        <img src="https://img.shields.io/badge/JPA-59666C?style=flat-square"/>
        <img src="https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white"/>
        <img src="https://img.shields.io/badge/JWT-000000?style=flat-square&logo=jsonwebtokens&logoColor=white"/>
        <img src="https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black"/>
      </p>
      <ul>
        <li>JWT 기반 인증/권한 처리</li>
        <li>Spring Security 설정</li>
        <li>AOP 기반 인증 공통화</li>
        <li>Controller 중복 인증 로직 제거</li>
        <li>포인트 상품 구매 기능 구현</li>
        <li>Optimistic Lock 기반 동시성 제어</li>
      </ul>
      <p>
        🔗 <a href="https://github.com/haarooo/ourassembly">Repository</a>
      </p>
    </td>
    <td width="33%" valign="top">
      <h3>⚡ checkmate</h3>
      <p>
        <b>AI-assisted rapid development 기반 실시간 협업 기능 구현 프로젝트</b>
      </p>
      <p>
        AI 도구를 활용해 빠르게 기능을 설계하고 구현한 프로젝트입니다.
        단순 CRUD를 넘어 WebSocket과 Firebase FCM을 활용한 실시간 기능 구현 경험을 담았습니다.
      </p>
      <p>
        <img src="https://img.shields.io/badge/AI Assisted-0878F8?style=flat-square"/>
        <img src="https://img.shields.io/badge/WebSocket-010101?style=flat-square"/>
        <img src="https://img.shields.io/badge/Firebase FCM-FFCA28?style=flat-square&logo=firebase&logoColor=black"/>
        <img src="https://img.shields.io/badge/Spring Boot-6DB33F?style=flat-square&logo=springboot&logoColor=white"/>
        <img src="https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black"/>
      </p>
      <ul>
        <li>AI 기반 빠른 기능 구현 흐름 경험</li>
        <li>WebSocket 기반 실시간 통신</li>
        <li>Firebase FCM 기반 알림 기능</li>
        <li>프론트엔드/백엔드 API 연동</li>
        <li>기능 구현 후 구조 개선 포인트 분석</li>
      </ul>
      <p>
        🔗 <a href="https://github.com/haarooo/checkmate">Repository</a>
      </p>
    </td>
  </tr>
</table>

<br/>

## 🔥 Problem Solving Highlights

### 1. AOP 기반 인증 공통화

반복되던 인증 확인 로직을 Controller에서 제거하고,  
AOP로 공통 관심사를 분리하여 코드 중복을 줄였습니다.

```java
@LoginCheck
@GetMapping("/mypage")
public ResponseEntity<?> getMyPage() {
    return ResponseEntity.ok(myPageService.getMyPage());
}
