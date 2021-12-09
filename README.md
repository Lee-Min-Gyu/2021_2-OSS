# Well-Dying
## Aim & Background
노인분들, 큰 질병에 걸리신 분들 등 시한부 분들 뿐만아니라
사람일은 어떻게 될지 모르는 것이기에 보통의 젊은 사람들까지 죽음에대하여 
미리 잘 준비하고 주변의 남은 사람들에게 추억과 메세지를 남겨주자함
<hr/>

## Development environment

![개발환경](https://user-images.githubusercontent.com/91940512/145427340-ddc2598f-0ff8-4986-901f-c89073ce155b.JPG)

* Firebase Authentiation-API

이메일/비밀번호 API를 사용하여 로그인, 회원 가입한 후 회원 정보를 FirebaseStoreDB에 저장

* Firebase Database

갤러리에서 구해온 사진을 액티비티에 넣어와 비트맵 형식으로 저장. 

User라는 데이터베이스 안에 회원 정보 및 사진, 동영상, 하고싶은 말 등을 저장하여 필요할 때 불러옴.

* Firebase Realtime Database

친한 친구 설정 및 설정된 친구에게 사용자가 죽은 뒤 사용자의 데이터베이스에 저장된 기록(사진 동영상 등) 전달.

Recycler View/ConstraintLayout/Scroll View 등을 활용하여 게시

* MySQL & PHP

APHP에 Get방식으로 사용자 정보값과 유언장 정보 실시간 업로드.


<hr/>

### 사진 선택/촬영 과 유언장 작성 페이지

![프젝 1](https://user-images.githubusercontent.com/91940512/145429339-08dcaba6-2570-44c3-8ac9-db27ffedd891.png)


### 유언장 날짜 볼 수 있는 페이지

![프젝2](https://user-images.githubusercontent.com/91940512/145429467-1e6bb993-de87-4edc-b0bc-f11654241e82.png)
