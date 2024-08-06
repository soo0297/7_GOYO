## 🎬 서비스 소개

TMDB (https://www.themoviedb.org/ )에서 제공하는 영화정보API를 활용한 영화추천 및 소개 서비스 입니다.

## 🔗배포주소

http://sss.com

<br>

## 🙌 팀(GO!YO!) 소개 및 구현사항

### 김진형

<details>
<summary>상세페이지 리뷰 작성 CRUD 제작</summary>
- *Write here!*<br>
- *Write here!*
</details>

### 안수영

<details>
<summary>카드 ‘상세보기’ 버튼 클릭하면 상세페이지로 이동</summary>
- 상세보기 버튼 만들기(movie.js / upcomMov.js 파일 innerHTML 내용으로 넣음)<br>
- 영화카드에 마우스 가져가면 '상세보기' 버튼 나타남(index.css 파일에서 hover기능)
- '상세보기' 버튼 클릭하면 상세페이지로 새창을 열지 않고 현재 페이지에서 이동(영화 id값 innerHTML에 입력)
- [참고링크](https://stickode.tistory.com/182)
</details>
<details>
<summary>상영예정작 API 불러오기</summary>
- upcomMov.js 파일에 상영예정작 API 불러와 카드 1개 내용 만들기<br>
- index.js 파일에서 카드 20개 로드
</details>
<details>
<summary>탭메뉴 구현 - 평점순 / 상영예정작</summary>
- 각 탭 클릭하면 해당 영화차트만 보여줌(index.js에서 구현)<br>
- [참고링크](https://abcdqbbq.tistory.com/88)
</details>

### 임보라

<details>
<summary>와이어프레임 제작</summary>
- *Write here!*<br>
- *Write here!*
</details>
<details>
<summary>메인페이지 배너</summary>
- *Write here!*<br>
- *Write here!*
</details>

### 홍연주

<details>
<summary>영화상세정보 및 출연진</summary>
 - Detail API(https://developer.themoviedb.org/reference/movie-details)를 이용해 영화 상세 정보를 불러와 화면에 표시<br>
 - Credits API(https://developer.themoviedb.org/reference/movie-credits)를 이용해 영화의 출연진 정보를 불러와 화면에 15개만 표시
</details>

<br>

## 💡 어려웠던 점, 해결한 내용

#### 홍연주

- 사소??한 실수를 찾는것이 제일 어려웠습니다<br>
  (세미콜론을 잘못 집어넣음, 변수명을 잘못 작성함, 함수에 return을 빼먹음, fetch에 options를 삭제해서 계속 api 오류가 뜸)<br>
- 여기저기서 찾아본 내용으로 코드를 짜다가 중복되는 코드, 필요없는 코드들이 생겨도 깔끔하게 합치는 것이 어려웠습니다.
  <br>

## 🎤 소감

#### 홍연주

좋은 분들을 만나 같이 개발하고 공유하는 과정에서 정말 많이 배웠습니다(특히 깃 사용법) 힘들었지만 뿌듯합니다
