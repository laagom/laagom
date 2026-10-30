# laagom

**고객의 업무 문제를 Java·SQL로 해결하는 B2B 엔터프라이즈 애플리케이션 엔지니어**

레거시 운영 환경에서 **성능 저하, 장애, 대용량 데이터 이관**처럼 원인이 잘 보이지 않는 문제를
로그와 실행계획, 재현 테스트로 끝까지 추적해 해결해 왔습니다.

- 기업용 웹 솔루션 개발·운영 **5년 이상**
- 10여 개 고객사의 그룹웨어(전자결재·메일·문서유통) **주담당**
- 요구사항 분석 → 설계·개발 → 검수·운영 반영까지 **고객과 직접 협업**
- 반복 업무는 스크립트와 AI 도구로 자동화

## 경력

| 기간 | 내용 |
|---|---|
| 2023.06 ~ 현재 | **B2B 그룹웨어 솔루션** — 고객사 유지보수·추가 개발, 성능·장애 대응, 외부 시스템 연동 |
| 2022.07 ~ 2023.05 | **기술 확장** — Python·Django 교육, Docker·AWS 배포, 팀·개인 프로젝트 |
| 2020.02 ~ 2022.06 | **웹 솔루션 개발·ERP 유지보수** — Spring Boot, JPA, MyBatis, MySQL, AWS |

## 주요 경험

- **대용량 데이터 이관** — 약 4만 건의 결재문서(약 100GB)를 독립 추출·검증 도구로 이관, 전수 교차검증으로 누락·무결성 오류 없이 완료
- **SQL 성능 개선** — 대용량 메일함 조회를 실행계획·인덱스·쿼리 구조 개선으로 7초대에서 0.2초대로 단축
- **장애 원인 분석** — 로그·OS 수치를 교차 확인하고 로컬에서 재현해 원인(파일 핸들 고갈)을 규명, 패치안과 재발방지안 작성. DB 커넥션풀 고갈 장애는 5~6초 쿼리를 1초 수준으로 개선
- **외부 시스템 연동·개발** — ERP 연동 결재 간소화, LDAP 대량 동기화, SMS 2차 인증 등 요구사항 분석부터 설계·개발·검수까지 수행
- **고객 협업** — 고객과 직접 기능 범위·일정·공수를 조율하고 운영 반영을 지원
- **업무 자동화** — 회사가 승인한 AI 도구로 분석·테스트·문서화 같은 반복 업무를 스킬과 스크립트로 체계화

## 기술

| 구분 | 내용 |
|---|---|
| 주력 | Java, SQL (Oracle · MSSQL · MySQL · MariaDB · Tibero), JSP/Servlet, Tomcat |
| 사용 경험 | Spring Boot, JPA, MyBatis, Python(Django), JavaScript, Linux, Docker, AWS(EC2 · RDS · S3) |
| 학습 중 | Spring Boot 심화, React · TypeScript, 테스트 코드 |
| 도구 | Git · GitLab, SVN, Maven · Ant, Playwright |

## 레포지토리

| 레포 | 설명 |
|---|---|
| [Spring-Demo](https://github.com/laagom/Spring-Demo) | Spring Boot 게시판. JPA·QueryDSL·MyBatis를 함께 사용한 계층형 구조 |
| [simple-web-scrap](https://github.com/laagom/simple-web-scrap) | Django로 만든 채용공고 스크랩 프로젝트 |
| [tech-notes](https://github.com/laagom/tech-notes) | 직접 실행해 보며 정리한 Spring, Java, Python 학습 노트 |
| [Algorithm](https://github.com/laagom/Algorithm) | 알고리즘 문제 풀이 |
