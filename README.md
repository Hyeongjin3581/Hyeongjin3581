<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0%3A0f172a%2C100%3A3b82f6&height=210&section=header&text=Hyeongjin%20Jung&fontSize=52&fontColor=ffffff&fontAlignY=38&animation=fadeIn&desc=Backend%20Developer%20%C2%B7%20Spring%20Boot%20%C2%B7%20JPA%20%C2%B7%20MySQL&descSize=18&descAlignY=60" width="100%" alt="Hyeongjin Jung · Backend Developer" />

<img src="https://readme-typing-svg.demolab.com?font=Noto%20Sans%20KR&weight=600&size=22&pause=1400&color=3B82F6&center=true&vCenter=true&width=620&height=48&lines=%EC%A1%B0%EC%9A%A9%ED%95%98%EC%A7%80%EB%A7%8C%2C%20%EB%A7%A1%EC%9D%80%20%EC%9D%BC%EC%9D%80%20%EB%81%9D%EA%B9%8C%EC%A7%80%20%ED%95%B4%EB%82%B4%EB%8A%94%20%EC%82%AC%EB%9E%8C%3B%EB%81%9D%EA%B9%8C%EC%A7%80%20%EB%93%A3%EA%B3%A0%2C%20%EC%B0%A8%EB%B6%84%ED%9E%88%20%EC%A0%84%ED%95%98%EB%8A%94%20%EC%82%AC%EB%9E%8C%3B%EC%96%B4%EC%A0%9C%EC%9D%98%20%EC%8B%A4%EC%88%98%EB%A5%BC%20%EC%98%A4%EB%8A%98%20%EB%B0%98%EB%B3%B5%ED%95%98%EC%A7%80%20%EC%95%8A%EB%8A%94%20%EC%82%AC%EB%9E%8C" alt="조용하지만, 맡은 일은 끝까지 해내는 사람" />

<br/>

<a href="mailto:poll3581@naver.com"><img src="https://img.shields.io/badge/Email-poll3581@naver.com-3B82F6?style=flat-square" /></a>
<a href="https://app.notion.com/p/KDT-7-6-12-28-39624243c2ee807593fce533ed30c01f"><img src="https://img.shields.io/badge/Notion-KDT_%EC%88%98%EC%97%85_%EC%A0%95%EB%A6%AC-000000?style=flat-square&logo=notion&logoColor=white" /></a>

</div>

<br/>

### 👋 About

- Java, Spring Boot, JPA, MySQL로 REST API를 만들어 온 신입 백엔드 개발자입니다.
- 업무 규칙을 코드로 옮기는 설계와 데이터 정합성(소프트 삭제, 유니크 제약, 동시성 제어)에 관심이 있습니다.
- 지금은 팀 프로젝트에서 맡았던 추천·배정 로직을 개인 프로젝트로 다시 설계하고 있습니다.

<br/>

### 🛠 Tech Stack

프로젝트에서 사용

<img src="https://skillicons.dev/icons?i=java,spring,mysql,react,js,html,css,python,tensorflow,opencv,raspberrypi,git,github&perline=13" alt="tech stack" />

수업에서 학습 &nbsp;
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
      <p>온케어의 추천·배정 로직을 다시 설계해, 동시 요청에도 중복 배정 없이 예약을 확정하는 API</p>
      <ul>
        <li>1주차: 엔티티 5개, 등록 API 7개, 공통 에러 응답, 테스트 11개</li>
        <li>30분 슬롯 규칙과 유니크 제약, <code>@Version</code>으로 중복 배정 방지 설계</li>
        <li>예정: N+1 측정과 개선, 락 방식 4가지 비교</li>
      </ul>
      <a href="https://github.com/Hyeongjin3581/visit-reservation-api">Repo 바로가기 →</a>
    </td>
    <td width="50%" valign="top">
      <h3>🏠 온케어 스케줄</h3>
      <p><b>정규 프로젝트 1</b> · 4인 팀 · 2026.09 ~ 10<br/>
      <code>Spring Boot</code> <code>JPA</code> <code>MySQL</code> <code>React</code></p>
      <p>방문요양 수급자와 요양보호사를 연결하는 일정 관리 서비스. 추천·결원 관리 백엔드를 맡았습니다.</p>
      <ul>
        <li>필수 조건 4가지로 거른 뒤 100점 점수(거리 50, 근무량 30, 연속 담당 20)로 상위 3명 추천</li>
        <li>방문 취소 시 같은 로직으로 대체 후보 재추천, React 관리자 화면 연동</li>
        <li>삭제 API 외래키 500 오류를 소프트 삭제로 바꿔 근무 이력 보존</li>
      </ul>
      <a href="https://github.com/Hyeongjin3581/kdt2026-project1-teamproject">Repo 바로가기 →</a>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <h3>🗑️ 센서스쿼드</h3>
      <p><b>졸업작품</b> · 성결대학교 팀 · 2025.09 ~ 2026.11<br/>
      <code>Raspberry Pi 4B</code> <code>TFLite</code> <code>OpenCV</code> <code>Python</code></p>
      <p>쓰레기통 적재량을 원격으로 확인하는 IoT 청소 보조 앱. 하드웨어와 AI를 맡았습니다.</p>
      <ul>
        <li>적재량 5단계 분류 모델을 3차례 학습해 엣지(TFLite)에서 추론</li>
        <li>판별 1회에 5프레임 평균, 신뢰도 60% 미만은 따로 표시해 오판 보완</li>
        <li>판별 결과를 서버와 DB에 저장하고 앱 푸시 알림까지 연동</li>
      </ul>
    </td>
    <td width="50%" valign="top">
      <h3>🔐 무인 장비 대여 플랫폼</h3>
      <p><b>미니 프로젝트 2</b> · 팀<br/>
      <code>Java</code> <code>JDBC</code> <code>MySQL</code></p>
      <p>JDBC 기반 MVC 대여 시스템. 대여·반납을 맡았습니다.</p>
      <ul>
        <li>장비 상태 검사, 대여, 상태 변경 흐름 구현</li>
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
| [kdt2026-springweb](https://github.com/Hyeongjin3581/kdt2026-springweb) | Spring Boot · JPA · JWT · Redis · WebSocket |
| [kdt2026-react](https://github.com/Hyeongjin3581/kdt2026-react) | React · Router · axios · STOMP · SSE |
| [kdt2026-backend](https://github.com/Hyeongjin3581/kdt2026-backend) | Java · MySQL · JDBC |
| [kdt2026-frontend](https://github.com/Hyeongjin3581/kdt2026-frontend) | HTML · CSS · JavaScript |
| [kdt2026-python](https://github.com/Hyeongjin3581/kdt2026-python) | Python |

<img src="https://capsule-render.vercel.app/api?type=waving&color=0%3A3b82f6%2C100%3A0f172a&height=110&section=footer" width="100%" alt="" />
