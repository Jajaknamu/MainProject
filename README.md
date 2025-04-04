# 교수님 백과사전

> Spring Boot 기반 강의 평가 / 교수 추천 서비스

## 💡 프로젝트 소개
교수 정보, 강의 후기, 추천 및 연구실 정보를 제공하는 백엔드 중심의 플랫폼입니다.  
학생들이 직접 교수님에 대한 평가를 남기고, 관심 있는 연구실 정보를 확인하며 지원할 수 있도록 도와줍니다.  
Ajax를 활용한 추천/관심 기능과 마이페이지 기능까지 포함된, 실사용을 고려한 CRUD 기반 서비스입니다.

## ⏱️ 개발 기간
- 2024.02 ~ 2024.04

## 👥 개발 인원
- 교수님 백과사전.v1 - 팀 프로젝트
- 
- 교수님 백과사전.v2 - 개인 프로젝트

## ⚙️ 개발 환경
- **Language** : Java 17
- **Framework** : Spring Boot 3.2.5
- **Template Engine** : Thymeleaf
- **ORM** : Spring Data JPA
- **Build Tool** : Gradle
- **Database** : MySQL
- **IDE** : IntelliJ IDEA
- **Version Control** : Git / GitHub

---

## 📌 주요 기능

### ✅ 회원 기능
- 회원가입 / 로그인 (Form, 소셜 로그인 구현 완료)
- 마이페이지: 이름/비밀번호 수정, 회원 탈퇴
- 내가 작성한 게시글 목록 확인 및 삭제/수정 가능

### ✅ 교수 기능
- 교수 등록 / 수정 / 삭제 (관리자 전용)
- 교수 상세 페이지에서 추천 수, 평균 평가 점수, 연구실 관심 수 확인 가능
- 교수별 강의평 게시글 리스트 제공

### ✅ 게시판 기능 (강의 평가)
- 교수 선택 후 강의평 등록 (출석, 강의력, 성적 평가 포함)
- 게시글 리스트 조회 / 상세보기 / 수정 / 삭제
- 제목 + 내용 기반 검색 기능 구현

### ✅ 댓글 기능
- 로그인한 사용자만 댓글 작성 가능
- 실시간 비동기 댓글 등록/출력 (Ajax 활용)

### ✅ 추천 / 관심 기능
- 교수 추천: 1인 1추천, 중복 추천 방지
  - 이미 추천한 경우 "추천을 취소하시겠습니까?" 확인창
- 연구실 관심 추가: 중복 여부 확인 및 토글 처리
- 모두 실시간 Ajax 처리 (화면 리로딩 없이 반영됨)

---

## 🎥 시연 이미지 / 영상

- 교수 상세 페이지 + 추천 기능  
  ![img1](https://github.com/user-attachments/assets/ed0c4415-0926-495c-b974-6acd7ce6f91a)

- 강의평 작성 및 검색  
  ![img2](https://github.com/user-attachments/assets/bb8843db-6894-4a6e-a24d-f7dc4d379cf1)

- 마이페이지 / 내가 쓴 글 관리  
  ![img3](https://github.com/user-attachments/assets/f2339f48-8423-4329-9057-e429be7791f0)

---

## 🧩 기술 스택

| Category    | Stack                                      |
|-------------|--------------------------------------------|
| Language    | Java 17                                    |
| Framework   | Spring Boot, Spring Security               |
| DB          | MySQL, Spring Data JPA                     |
| Frontend    | Thymeleaf, HTML/CSS, JavaScript, AJAX      |
| Tools       | IntelliJ, Git, GitHub, MySQL Workbench     |

---

## 📌 향후 개선 예정 사항

- 관리자 기능 고도화: 교수 통계 관리 및 게시글 모니터링
- REST API + Vue 또는 React로 프론트엔드 리팩토링
- CI/CD 파이프라인 및 AWS 배포 환경 구성

---

> 📬 문의: heyfer6867@gmail.com  
> 💼 포트폴리오: [노션 링크 삽입](https://notion.so/yourportfolio)  
