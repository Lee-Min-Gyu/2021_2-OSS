# Well-Dying
## Aim & Background
### 개발 배경

언제 다가올지 모르는 죽음에 대해 미리 생각하고 좋았던 추억이 담긴 사진, 동영상과 사용자의 유언장을 통해 죽음을 긍정적으로 대비 할 수 있도록 돕고자 개발하게 되었다. 

     이 어플의 핵심은 자신의 추억이 담긴 사진 동영상 등을 지인들과 공유하며 긍정적으로 죽음을 받아 들이도록 하는 것이다.

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
