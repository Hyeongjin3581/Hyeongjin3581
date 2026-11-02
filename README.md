<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0%3A0f172a%2C100%3A3b82f6&height=210&section=header&text=Hyeongjin%20Jung&fontSize=52&fontColor=ffffff&fontAlignY=38&animation=fadeIn&desc=Backend%20Developer%20%C2%B7%20Spring%20Boot%20%C2%B7%20JPA%20%C2%B7%20MySQL&descSize=18&descAlignY=60" width="100%" alt="Hyeongjin Jung · Backend Developer" />

<img src="https://readme-typing-svg.demolab.com?font=Noto%20Sans%20KR&weight=600&size=22&pause=1400&color=3B82F6&center=true&vCenter=true&width=620&height=48&lines=%EB%8D%B0%EC%9D%B4%ED%84%B0%EA%B0%80%20%EB%81%9D%EA%B9%8C%EC%A7%80%20%EC%A0%95%ED%99%95%ED%95%98%EA%B2%8C%20%ED%9D%90%EB%A5%B4%EB%8F%84%EB%A1%9D%20%EC%84%A4%EA%B3%84%ED%95%A9%EB%8B%88%EB%8B%A4%3B%EC%B6%94%EC%B2%9C%C2%B7%EB%B0%B0%EC%A0%95%20API%EB%B6%80%ED%84%B0%20IoT%20%EB%8D%B0%EC%9D%B4%ED%84%B0%20%EC%97%B0%EB%8F%99%EA%B9%8C%EC%A7%80%3B%EB%8F%99%EC%9E%91%ED%95%98%EB%8A%94%20%EC%BD%94%EB%93%9C%EB%A5%BC%20%EB%84%98%EC%96%B4%2C%20%EC%9D%B4%EC%9C%A0%EB%A5%BC%20%EC%84%A4%EB%AA%85%ED%95%A0%20%EC%88%98%20%EC%9E%88%EB%8A%94%20%EC%BD%94%EB%93%9C" alt="데이터가 끝까지 정확하게 흐르도록 설계합니다" />

<br/>

<a href="mailto:poll3581@naver.com"><img src="https://img.shields.io/badge/Email-poll3581@naver.com-3B82F6?style=flat-square" /></a>
<a href="https://app.notion.com/p/KDT-7-6-12-28-39624243c2ee807593fce533ed30c01f"><img src="https://img.shields.io/badge/Notion-KDT_%EC%88%98%EC%97%85_%EC%A0%95%EB%A6%AC-000000?style=flat-square&logo=notion&logoColor=white" /></a>

</div>

<br/>

### 👋 About

- **신입 백엔드 개발자** — Java · Spring Boot · JPA · MySQL로 REST API를 설계하고, 화면과 기기까지 데이터를 연결해 왔습니다.
- **관심사** — 업무 규칙을 코드로 옮기는 설계, 그리고 **데이터 정합성** (소프트 삭제, 유니크 제약, 동시성 제어)
- **지금** — 팀 프로젝트에서 맡았던 추천·배정 로직을 개인 프로젝트로 다시 설계하며, 개선 결과를 수치로 기록하고 있습니다.

<br/>

### 🛠 Tech Stack

**프로젝트에서 사용**

<img src="https://skillicons.dev/icons?i=java,spring,mysql,react,js,html,css,python,tensorflow,opencv,raspberrypi,git,github&perline=13" alt="tech stack" />

**수업에서 학습** &nbsp;
![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white)
![JWT](https://img.shields.io/badge/JWT-000000?style=flat-square&logo=jsonwebtokens&logoColor=white)
![WebSocket](https://img.shields.io/badge/WebSocket·SSE-4A5568?style=flat-square)
![Jira](https://img.shields.io/badge/Jira-0052CC?style=flat-square&logo=jira&logoColor=white)

<br/>

### 🚀 Featured Projects <sub>최신순</sub>

<table>
  <tr>
    <td width="50%" valign="top">
      <h3>📅 Visit Reservation API</h3>
      <p><b>개인 프로젝트</b> · 2026.10 ~ 진행 중<br/>
      <code>Java 21</code> <code>Spring Boot 4.1</code> <code>JPA</code> <code>MySQL</code></p>
      <p>온케어의 추천·배정 로직을 다시 설계해, <b>동시 요청에도 중복 배정 없이</b> 예약을 확정하는 API</p>
      <ul>
        <li>1주차: 엔티티 5개 · 등록 API 7개 · 공통 에러 응답 · <b>테스트 11개 통과</b></li>
        <li>30분 슬롯 규칙 + 유니크 제약 · <code>@Version</code>으로 중복 배정 방지 설계</li>
        <li>예정: N+1 측정·개선, 락 4가지(유니크 / 비관적 / 낙관적 / Redis) 비교</li>
      </ul>
      <a href="https://github.com/Hyeongjin3581/visit-reservation-api">Repo 바로가기 →</a>
    </td>
    <td width="50%" valign="top">
      <h3>🏠 온케어 스케줄</h3>
      <p><b>정규 프로젝트 1</b> · 4인 팀 · 2026.09 ~ 10<br/>
      <code>Spring Boot</code> <code>JPA</code> <code>MySQL</code> <code>React</code></p>
      <p>방문요양 수급자와 요양보호사를 연결하는 일정 관리 서비스 — <b>추천 · 결원 관리 백엔드 담당</b></p>
      <ul>
        <li>필수 조건 4가지로 거른 뒤 <b>100점 점수</b>(거리 50 · 근무량 30 · 연속 담당 20)로 상위 3명 추천</li>
        <li>방문 취소 시 같은 로직으로 대체 후보 재추천, React 관리자 화면 연동</li>
        <li>🔧 삭제 API 외래키 500 오류 → <b>소프트 삭제</b>로 전환해 근무 이력 보존</li>
      </ul>
      <a href="https://github.com/Hyeongjin3581/kdt2026-project1-teamproject">Repo 바로가기 →</a>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <h3>🗑️ 센서스쿼드</h3>
      <p><b>졸업작품</b> · 성결대학교 팀 · 2025.09 ~ 2026.11<br/>
      <code>Raspberry Pi 4B</code> <code>TFLite</code> <code>OpenCV</code> <code>Python</code></p>
      <p>쓰레기통 적재량을 원격으로 확인하는 IoT 청소 보조 앱 — <b>하드웨어 · AI 담당</b></p>
      <ul>
        <li>적재량 <b>5단계</b> 분류 모델을 <b>3차례</b> 학습해 엣지(TFLite)에서 추론</li>
        <li>판별 1회에 <b>5프레임 평균</b>, 신뢰도 60% 미만은 따로 표시해 오판 보완</li>
        <li>판별 결과를 서버 · DB 저장 → 앱 푸시 알림까지 연동</li>
      </ul>
    </td>
    <td width="50%" valign="top">
      <h3>🔐 무인 장비 대여 플랫폼</h3>
      <p><b>미니 프로젝트 2</b> · 팀<br/>
      <code>Java</code> <code>JDBC</code> <code>MySQL</code></p>
      <p>JDBC 기반 MVC 대여 시스템 — <b>대여 · 반납 담당</b></p>
      <ul>
        <li>장비 상태 검사 → 대여 → 상태 변경 흐름 구현</li>
        <li>반납 상태에 따라 대여가능 / 점검중 분기</li>
      </ul>
      <a href="https://github.com/Hyeongjin3581/kdt2026-mini2-teamproject">Repo 바로가기 →</a>
    </td>
  </tr>
</table>

<br/>

### 📚 KDT 2026 학습 저장소

> AI 딥러닝 중심의 자바 프론트엔드·백엔드 풀스택 과정 (성결대학교 산학협력단, 2026.07 ~ 2026.12)

| 저장소 | 내용 |
| --- | --- |
| [kdt2026-mini1-teamproject](https://github.com/Hyeongjin3581/kdt2026-mini1-teamproject) | 미니 프로젝트 1 · 담배 리뷰 커뮤니티 (HTML · CSS · JS · localStorage) |
| [kdt2026-springweb](https://github.com/Hyeongjin3581/kdt2026-springweb) | Spring Boot · JPA · JWT · Redis · WebSocket |
| [kdt2026-react](https://github.com/Hyeongjin3581/kdt2026-react) | React · Router · axios · STOMP · SSE |
| [kdt2026-backend](https://github.com/Hyeongjin3581/kdt2026-backend) | Java · MySQL · JDBC |
| [kdt2026-frontend](https://github.com/Hyeongjin3581/kdt2026-frontend) | HTML · CSS · JavaScript |
| [kdt2026-python](https://github.com/Hyeongjin3581/kdt2026-python) | Python |

<img src="https://capsule-render.vercel.app/api?type=waving&color=0%3A3b82f6%2C100%3A0f172a&height=110&section=footer" width="100%" alt="" />
