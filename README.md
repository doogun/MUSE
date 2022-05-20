# 관통 PJT



### MUSE

- member
  - 박준영
  - 권도건



- description
  - tmdb api를 활용한 영화 추천 서비스
  - 영화인(배우, 감독, 관객)들의 소통을 위한 커뮤니티



- tools
  - Django
  - Javascript
  - REST API
  - HTML / CSS (Bootstrap 활용)

---

### 일정

- 전체일정
  - 기본개발 (5/20)
    - 메인페이지
    - 영화 목록
    - 영화 세부사항
      - 평점 등록, 수정, 삭제 가능
    - 좋아요 구현
    - 회원가입
    - 로그인 / 로그아웃
    - 팔로우
  - 추천 알고리즘 (5/23)
    - 조건부 랜덤
      - 유저가 좋아요를 한 영화의 장르에 맞춰 추천
      - 좋아요 누른 것이 없다면 랜덤으로 추천
  - 검색 (5/24)
    - `in`으로 구현
    - `LCS`로 구현
  - 커뮤니티 (5/25)
    - 기본구현
      - 모든 유저가 글과 댓글을 등록, 수정, 삭제 가능
      - 작성자의 이름을 클릭하면 프로필 페이지로 이동

---

## 05/20

- 계획
  - 기본개발
    - 메인페이지
      - 네브바(로그인, 회원가입 등)
      - 메인페이지 이미지
      - 참고자료 : https://campaign.naver.com/aihackathon_speech/
    - 영화 목록
      - 카드 형식 (Bootstrap 활용)
      - Grid System (Bootstrap 활용)
      - 영화별 좋아요 버튼 삽입
    - 영화 세부사항
      - 평점 & 리뷰 삽입, 수정, 삭제하는 버튼 (평점은 필수, 리뷰는 선택)
      - 영화별 좋아요 버튼 삽입
    - 프로필
      - 팔로잉 / 팔로워
      - 팔로워 버튼 구현
      - 좋아요 누른 영화목록 (제목으로 표시, 제목을 누르면 세부사항 페이지로 이동)
- 디자인
  - ERD 작성
    - User table, Movie table, Genre table
    - ![image-20220520142052896](README.assets/image-20220520142052896-16530240555071.png)
  - Figma 작성
    - https://www.figma.com/file/hSXRPPqkZssuZNqzbXHnuV/Untitled?node-id=0%3A1
    - ![image-20220520160622413](README.assets/image-20220520160622413-16530303841791.png)
- 개발
  - 
- 테스트
  - 

- 검토
  - 







































