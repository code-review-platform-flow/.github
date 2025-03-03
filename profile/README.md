# Flow - 코드 리뷰 플랫폼 (https://front.gcuflow.site - 종료)

**Flow**는 대학생과 졸업생을 위한 혁신적인 개발 커뮤니티 플랫폼으로,<br/> 신뢰 기반의 코드 리뷰 및 멘토링 서비스를 제공하여 개발자 커뮤니티의 한계를 극복하고자 합니다.

---

## 📌 프로젝트 개요

### 프로젝트 요약
Flow는 다음과 같은 기능과 특징을 제공합니다:
- **커뮤니티 서비스**: 트렌딩 포스트, 글 작성 및 댓글 기능으로 사용자 참여 유도
- **코드 리뷰**: 신뢰 기반의 피드백 시스템
- **커피챗 멘토링**: 학교 인증된 계정으로 졸업생 멘토와 상담 가능
- **채용 정보 제공**: API를 통한 최신 취업 정보
- **명예의 전당**: 우수 기여 사용자들을 위한 동기부여 시스템

---

## 🖼 주요 화면

### 1. 메인 페이지
- 트렌딩 포스트, 명예의 전당 및 채용 정보 확인

| 웹 화면                               | 모바일 화면                           |
|---------------------------------------|---------------------------------------|
| ![웹 화면](https://github.com/user-attachments/assets/13133192-5af3-4f00-8d43-dbf46d7c8a8c) | ![모바일 화면](https://github.com/user-attachments/assets/79dc4205-e429-4c42-a249-32382237888c) |



### 2. 게시글 관리
![Post Feature](https://github.com/user-attachments/assets/c422c3fd-5310-4545-a56b-da4656f2aafe)

| 웹 화면                               | 모바일 화면                           |
|---------------------------------------|---------------------------------------|
| ![웹 화면](https://github.com/user-attachments/assets/36d1f2fa-fad7-4bba-8e3a-3d3d4f26056c) | ![모바일 화면](https://github.com/user-attachments/assets/3bb4f78b-c611-4a2e-ab46-26f7ae6ce6a3) |

### 3. 커피챗 관리
- 커피챗 요청 및 결제
![Coffee Chat](https://github.com/user-attachments/assets/36d1f2fa-fad7-4bba-8e3a-3d3d4f26056c)

---

## ☁ 클라우드 아키텍처

### 시스템 구성도
![클라우드 아키텍처](https://media-cdn.atlassian.com/file/754afe90-adeb-459a-ab94-53f077342b60/image/cdn?allowAnimated=true&client=daef7aef-6c7c-4794-85da-f8155ef1605d&collection=contentId-557076&height=390&max-age=2592000&mode=full-fit&source=mediaCard&token=eyJhbGciOiJIUzI1NiJ9.eyJpc3MiOiJkYWVmN2FlZi02YzdjLTQ3OTQtODVkYS1mODE1NWVmMTYwNWQiLCJhY2Nlc3MiOnsidXJuOmZpbGVzdG9yZTpjb2xsZWN0aW9uOmNvbnRlbnRJZC01NTcwNzYiOlsicmVhZCJdfSwiZXhwIjoxNzM1MDQ2ODkwLCJuYmYiOjE3MzUwNDQwMTB9.zCxi5Xl_PK4Ww2l-ko7R0GRjNCjTAwuJ2Kb3lOM5gQs&width=760)

### 설명
- **Compute Engine**: Google Cloud의 인스턴스 기반 애플리케이션 실행
- **API Gateway**: 사용자 요청을 라우팅
- **Kubernetes**: 배포 관리 및 상태 모니터링
- **Artifact Registry**: 컨테이너 이미지 저장소
- **Grafana & Prometheus**: 모니터링 및 알림 시스템

---

## 📂 소스 코드 구조

### 주요 레포지토리
1. **프론트엔드**: 사용자 인터페이스 개발 (React, Next.js)
   - `flow-web`
   - `flow-admin-dashboard`
2. **백엔드**: 비즈니스 로직 및 데이터 관리 (Spring Boot)
   - `flow-main`
   - `flow-api-gateway`
   - `flow-payment`
   - `flow-admin-main`
3. **DevOps**: CI/CD 및 배포 관리 (Terraform, Kubernetes)
   - `flow-terraform`
   - `flow-manifest`

---

## 🔧 기술 스택

### 프론트엔드
- React, Next.js
- TypeScript
- Styled-components

### 백엔드
- Spring Boot
- PostgreSQL
- JWT 인증

### DevOps
- Google Cloud Platform (GCP)
- Kubernetes
- ArgoCD
- Terraform

---

## 👥 팀 구성원

| 역할                | 이름       | Github                      |
|---------------------|-----------|----------------------------|
| 팀장 / Frontend   | Ji Min Seong    | https://github.com/jiminseong    |
| Backend / DevOps        | Park Chan Young    | https://github.com/steamedEggMaster   |
| DevOps / Frontend / Backend      | abwarten    | https://github.com/abwarten      |

---

## 🔗 주요 링크
- [서비스 URL](https://front.gcuflow.site)
- [서비스 소개 영상](https://www.youtube.com/watch?v=xUex9mmyuQU)

