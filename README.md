# 1. 프로젝트 개요

<img src='https://user-images.githubusercontent.com/76957700/191293642-d0933653-bf98-469c-b9c9-bcb7add863d3.png' width=500 height=200/>





> **Maplix는 드라마, 영화, 예능 등의 촬영지에 대한 정보를 제공하고 이를 기반으로 여행을 할 수 있도록 직접 코스를 짤 수 있게하는 새로운 유형의 여행 일정 제공 및 기록 서비스 입니다.** 
- **미디어 촬영지**를 포함한 여행 코스 추천
- 사용자가 **직접** 미디어 촬영지를 포함한 여행코스를 짜도록 도움
- 촬영지 여행 일정을 **특별하게 기록**

# 2. 사용 기술
- React.js
- Node.js, Express
- MySQL
- Nginx, AWS EC2


# 3. 주요 기능
![image](https://user-images.githubusercontent.com/76957700/191293702-d9e8fa45-906a-490d-8051-97dd435b1000.png)

![image](https://user-images.githubusercontent.com/76957700/191293940-cf1f69a3-286b-4486-966e-7824f008ed12.png)

![image](https://user-images.githubusercontent.com/76957700/191294065-c2ac395f-89f4-45bf-8054-ae6dc6393ea2.png)

# 4. 활용데이터
- 카카오맵 API
	-  지도 검색, 장소 정보
- 한국관광공사 두루누비 정보 서비스 API
	- 추천 코스 탭 제공
- 공공데이터포탈
	- 드라마 촬영지 정보 파일
- 직접 수집한 촬영지 정보 데이터

# 5. 담당 역할
-   검색 페이지
	- 미디어 제목 / 지역명 검색시 데이터 가져오기
	- 필터 기능
-   상세 페이지 
	- 즐겨찾기 추가
- 코스 생성 페이지
	- 필터 기능
	- 내 코스에 추가 기능
-   커뮤니티 페이지
-   카카오맵 API와 연동



#  6. API 명세서 (작성중 ,,,)


|  |  |  |  |
|--|--|--|--|
| 검색 | /search/area |지역명으로 검색|get
||/search/title|미디어명으로 검색|get
||/post/likelist|검색 결과에서 즐겨찾기에 추가|post
|코스|/course|코스 생성하는 탭으로 이동|get
|커뮤니티|/community|커뮤니티에 올라온 글 반환| get
|  |/community/writepost  |커뮤니티에 글쓰기|post
|마이페이지 | /likelist| 즐겨찾기한 장소 반환| |
||/mycourse|내 경로에 추가한 코스 정보 반환||
| |/mypage/request|요청하기 기능|post
||/mypage/stamp|도장찍기 기능||
|회원가입|/checkid|아이디 중복 확인||
||/checknickname|닉네임 중복 확인||
||/signup|회원정보 등록|
|로그인|/login|
|--|--|


