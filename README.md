# GSITM-CodeChef
### 📘 소개

**사용자 중심의 예약·리뷰·관리 기능을 갖춘 식당 예약 플랫폼 구축. 
Netfilx 시리즈 ‘흑백요리사’ 컨셉을 기반으로 식당 정보를 한 눈에 확인하고 간편하게 이용할 수 있도록 구현**

- **진행 기간**: 2024.10.18 - 11.03
- **팀 이름:** codechef
- **팀 구성**: 6인 (풀스택)

### 🛠 기술 스택

- **Frontend**: HTML, CSS, JavaScript, JQuery, Thymeleaf, Bootstrap
- **Backend**: Java, Spring Boot, Spring Data JPA, Spring Security, AJAX
- **Database**: PostgreSQL (ERD 설계 참여)
- **Infra/Tool**: AWS EC2, S3, IntelliJ, DBeaver, GitHub, Figma

### **🧱 주요 기능 요약**

Netflix 시리즈 ‘흑백요리사’에 소개된 식당을 키워드 및 카테고리 기반으로 탐색하고, 로그인 후 예약과 리뷰 작성까지 가능한 통합 플랫폼으로, 예약 → 방문 → 리뷰까지의 흐름을 사용자 중심으로 설계했습니다. 식당별 상세 정보와 지도, 메뉴를 제공하며, 리뷰 이미지 파일은 AWS S3에 업로드하고 URL로 관리하여 안정성과 확장성도 확보했습니다.

### **👩‍💻 담당 기능 요약**

🔹 **Fullstack 개발 (프론트엔드 + 백엔드 + S3 연동 + DB 설계 일부 참여)**

- 식당 상세 페이지 구현: 매장 정보, 메뉴 목록, 리뷰 평균, Google Maps 연동 등 UI 구성 및 Thymeleaf 처리
- 리뷰 작성/조회 기능 구현 (유효성 검사, S3 이미지 업로드)
- 마이페이지 구현: 예약(예정/완료), MY 리뷰 리스트 출력
- 방문 완료 페이지 구현: 예약 상태 기반으로 리뷰 여부 분기 출력
