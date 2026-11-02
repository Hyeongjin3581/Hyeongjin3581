## 👋 Hyeongjin3581

![Java](https://img.shields.io/badge/Java-21-ED8B00?style=flat-square&logo=openjdk&logoColor=white)
![Spring Boot](https://img.shields.io/badge/Spring_Boot-6DB33F?style=flat-square&logo=springboot&logoColor=white)
![JPA](https://img.shields.io/badge/JPA/Hibernate-59666C?style=flat-square&logo=hibernate&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white)
![JWT](https://img.shields.io/badge/JWT-000000?style=flat-square&logo=jsonwebtokens&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)

![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![React](https://img.shields.io/badge/React-19-61DAFB?style=flat-square&logo=react&logoColor=black)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat-square&logo=css&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)

---

### 🧩 About (Learning)

- **Backend** : Java / Spring Boot (Spring Data JPA · JWT · Redis · WebSocket · SSE)
- **DB** : MySQL / Redis
- **Frontend** : JavaScript / HTML · CSS / React
- **Experience**
  - **정규 프로젝트 · 온케어 스케줄**
    - API 명세서와 DB 테이블 설계를 먼저 정리하고, Spring Boot · JPA로 보호자 · 수급자 · 문의 CRUD API를 만들어 React 화면과 연결해 백엔드 · 프론트에 모두 적용했습니다.
    - 거절 · 취소된 방문을 결원으로 판정하고 거리 · 근무량 · 연속성 점수로 대체 요양보호사 상위 3명을 다시 추천하도록 구현해, 결원 관리 화면에서 바로 재배정할 수 있게 적용했습니다.
  - **미니 프로젝트 2 · 무인 장비 대여**
    - Java · JDBC의 MVC 구조로 대여 · 반납 기능을 나누고, RentalDAO에서 장비 상태 검사 → 대여 → 상태 변경 순서로 MySQL에 반영하도록 적용했습니다.
    - 반납할 때 장비 상태에 따라 대여가능 / 점검중으로 나눠 상태값을 갱신해, 점검이 필요한 장비는 다시 대여되지 않도록 적용했습니다.
  - **미니 프로젝트 1 · 담배 리뷰 커뮤니티**
    - HTML · CSS · JavaScript로 커뮤니티 · 상세 페이지를 만들고, 게시글 · 리뷰 데이터를 localStorage에 저장해 서버 없이 작성 · 조회가 되도록 적용했습니다.
    - 기능마다 Git 브랜치를 나눠 작업하고 merge로 팀원들의 코드를 합치며 협업 흐름을 익혔습니다.

---

### 🚀 Featured Projects

<table>
  <tr>
    <td width="50%" valign="top">
      <h3>🏠 온케어 스케줄</h3>
      <p>방문요양 일정 관리 · 요양보호사 추천 플랫폼 (Spring Boot · React)</p>
      <ul>
        <li>추천 점수 (거리 50 · 근무량 30 · 연속성 20) 상위 3명</li>
        <li>결원 관리 · 대체 후보 재추천 (백엔드 + 프론트)</li>
      </ul>
      <a href="https://github.com/Hyeongjin3581/kdt2026-project1-teamproject">Repo 바로가기 →</a>
    </td>
    <td width="50%" valign="top">
      <h3>📅 Visit Reservation API <sub>(진행중)</sub></h3>
      <p>온케어에서 맡은 추천 · 배정 로직을 다시 설계하는 개인 프로젝트</p>
      <ul>
        <li>동시 요청에도 중복 배정 없는 예약 확정</li>
        <li>N+1 개선 · 동시성 제어 4가지 비교 (예정)</li>
      </ul>
      <a href="https://github.com/Hyeongjin3581/visit-reservation-api">Repo 바로가기 →</a>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <h3>🔐 무인 장비 대여 플랫폼</h3>
      <p>JDBC 기반 MVC 대여 시스템 (Java · JDBC · MySQL)</p>
      <ul>
        <li>대여 & 반납 담당 : 장비 상태 검사 → 대여 → 상태 변경</li>
        <li>반납 상태에 따라 대여가능 / 점검중 분기</li>
      </ul>
      <a href="https://github.com/Hyeongjin3581/kdt2026-mini2-teamproject">Repo 바로가기 →</a>
    </td>
    <td width="50%" valign="top">
      <h3>📝 Notes</h3>
      <p>KDT 2026 수업 · 개발 기록</p>
      <ul>
        <li>HTML · CSS · JS → Java · DB → Spring · React 날짜별 정리</li>
        <li>프로젝트 회고 · 면접 대비 정리</li>
      </ul>
      <!-- TODO: 아래 href를 Notion 공개 링크로 바꾸기 -->
      <a href="https://github.com/Hyeongjin3581?tab=repositories">Notes 바로가기 →</a>
    </td>
  </tr>
</table>

---

### 📚 KDT 2026 학습 저장소

| 저장소 | 내용 |
| --- | --- |
| [kdt2026-frontend](https://github.com/Hyeongjin3581/kdt2026-frontend) | HTML · CSS · JavaScript |
| [kdt2026-backend](https://github.com/Hyeongjin3581/kdt2026-backend) | Java · MySQL · JDBC |
| [kdt2026-springweb](https://github.com/Hyeongjin3581/kdt2026-springweb) | Spring Boot · JPA · JWT · Redis · WebSocket |
| [kdt2026-react](https://github.com/Hyeongjin3581/kdt2026-react) | React · Router · axios · STOMP · SSE |
| [kdt2026-python](https://github.com/Hyeongjin3581/kdt2026-python) | Python |
| [kdt2026-mini1-teamproject](https://github.com/Hyeongjin3581/kdt2026-mini1-teamproject) | 미니프로젝트 1 · 담배 리뷰 커뮤니티 (HTML · CSS · JS) |

---

### 📫 Contact

- Email : [poll3581@naver.com](mailto:poll3581@naver.com)
<!-- TODO: Notion 공개 링크가 생기면 아래 줄의 주석을 풀고 링크를 넣기 -->
<!-- - Blog : [Notion](여기에-Notion-공개-링크) -->
