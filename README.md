# 일일 기록
## 230206
- Github page index 생성

## 230207
- `목표설정` 기본적인 CRUD 앱 구현
- `Github 페이지 레이아웃 설정` Figma 사용

![[Github page 레이아웃.png]](https://github.com/riumr/riumr.github.io/blob/6de7e89055ee03444e1264ae1f3c70c73d05373c/Github%20page%20%EB%A0%88%EC%9D%B4%EC%95%84%EC%9B%83.png)

## 230208
- `Bootstrap` 적용
- `레이아웃` 구성

## 230209
- `앱 레이아웃 설정 및 첨부` Figma 사용

## 230210
- `데이터 모델 설계` 데이터 테이블 사용

![[ERD-diagram.svg]](https://github.com/riumr/riumr.github.io/blob/a9d322b55efc1677b6d7d1d303d174972b0e1c2d/ERD-diagram.svg)

## 230211
- `django` 개발환경 구성 및 기본설정

## 230212
- `crud 앱` 레이아웃 구성

## 230213
- `crud 앱` 기능과 API 주소 설정

![[기능과 주소.svg]](https://github.com/riumr/riumr.github.io/blob/19c57aac9c3a1d4f12cd1f0d74e4957c1dac562b/%EA%B8%B0%EB%8A%A5%EA%B3%BC%20%EC%A3%BC%EC%86%8C.svg)

## 230214
- `model`, `view`, `url` 기본 구성

## 230215
- 데이터 테이블 `생성` 및 `migration`

## 230216
- index 페이지(index.html)에 `테이블` 생성

## 230217
- `bootstrap` 적용 및 `create` 기능 작성

## 230218
- 중간점검

## 230219
- `container` 스타일 적용

## 230220
- `create` 페이지에 `bootstrap` 적용

## 230221
- `create` 기능 구현 : 값 입력 후 등록하면 index 페이지에 출력

## 230222
- `index`,`create` 페이지 수정

## 230223
- `detail` 페이지 연결 및 작성

## 230224
- `update`,`delete` 기능 구현 및 페이지 구성

## 230227
- `index` 페이지 스타일 수정

## 230228
- 전체 페이지 스타일 수정 : `contents` 위치, 크기

## 230301
- `detail`, `create`, `update` 페이지 스타일 수정

## 230302
- `create`, `update` 페이지 스타일 수정 : border 세로 높이 조절.
- `form title`에 `required` 요소 추가

## 230303
- `detail_public` 페이지 생성

## 230304
- `login` 앱 생성

## 230305
- `login` 앱 이름 변경 (-> `accounts`)
- `accounts` 기본 설정 (`url`,`views`,`templates`)

## 230306
- accounts `login`, `signup` 페이지 작성

## 230307
- `signup` 기능 구현 : `django user object` 사용

## 230308
- `login`, `signup` 레이아웃 수정

## 230309
- `login` 기능 구현 : `django authentication` 사용

## 230310
- `index` 페이지에 `회원가입`,`로그인` 버튼 생성 및 연결

## 230311
- `회원가입`, `로그인` 페이지에 `목록` 버튼 생성
- `회원가입`, `로그인` 코드 보완 : 성공 시 목록으로 redirect

## 230312
- `login auth 과정` 코드 보완

## 230313
- `AUTH_USER_MODEL` 설정

## 230314
- `admin`에 `crud model`,`user model` 등록

## 230315
- `login` 기능 코드 수정

## 230316
- `좋아요` template, view, url, model 생성

## 230317
- `좋아요` 기능 코드 작성

## 230318
- `좋아요` 기능 테스트 및 수정

## 230319
- `redis` 설치 및 설정 추가

## 230320
- `postgres` 설정 추가

## 230321
- `accounts`에 `redis` 적용

## 230322
- `redis` 활용 로그인 코드 작성

## 230323
- 작성한 로그인 코드 작동 확인

## 230324
- 유저 패스워드 `암호화` 코드 작성
- `로그아웃` 코드 작성

## 230327
- `로그아웃` 코드 보완

## 230328
- `인증`시 index 페이지 연결

## 230329
- `인증`시 index 페이지 연결 수정
- `로그아웃`시 기본 index 페이지 연결

## 230330
- 로그인시에만 `좋아요` 기능이 작동하도록 수정

## 230331
- `좋아요` 모델 수정 : `유저정보` model을 외래키로 추가

## 230401
- `좋아요` 기능시 `유저정보` model 추가되도록 코드 수정

## 230402
- `좋아요` 기능시 `UserLiked` model에 `유저정보` 가 추가되도록 구현
- `회원가입`시 회원정보가 저장되지 않는 점 fix

## 230403
- `회원가입`시 비밀번호 암호화 방법 변경
- `로그인` 시 비밀번호 체크 과정 update

## 230404
- `비밀번호` 체크 코드 지속적인 오류로 비활성화 처리

## 230405
- `유저 profile` 페이지 생성

## 230406
- `유저 활동`, `Article`  model 생성
- view의 변수명 변경(Index -> Article)

## 230407
- `Article` model에 `CustomUser` foreignkey 추가

## 230408
- 변경된 `model` migrate
- 서버 실행 테스트

## 230409
- 글 작성시 `user` 모델 추가되도록 `view` 수정

## 230410
- 오류가 있어 `CustomUser` 모델로 구현했던 `회원기능`에 `django authenication system` 다시 적용

## 230411
- `django authentication system` 으로 `signup`, `login`, `logout` 재구현

## 230412
- 코드 수정 및 서버 실행 테스트

## 230413
- 회원가입시 비밀번호가 이메일필드에 입력되는 문제 발견 및 해결

## 230414
- `유저 로그인`시 로그인한 유저용 페이지로 이동되도록 `Index` view 수정

## 230415
- `로그아웃` 코드 함수명 수정(logout -> user_logout) : 로그아웃 작동시 함수명 중복으로 발생 오류 해결

## 230416
- `좋아요` 코드 수정 : 유저 인증 `is_authorized` 로 수정

## 230417
- `작성하기` 코드 수정 : 작동시 django 기본 user model 추가
- `UserActivity` model 수정 : `CustomUser` -> django 기본 user model

## 230418
- `작성하기` 코드 수정 : 작동시 `인증된 user` `article` model에 추가.
   `article` 에 추가된 글 `index`에 추가

## 230419
- `좋아요` 기능 작동하지 않는 점 발견

## 230420
- `좋아요` 기능 오류 fix

## 230421
- `유저활동` model update

## 230422
- `유저가 쓴 글` 을 `user_page` 에 보여주는 코드 작성
- `로그인` 으로 인증시 글 작성할 수 있도록 코드 수정

## 230423
- `user_page` 에 로그인한 유저의 글만 보이도록 수정
- 중복된 글을 `좋아요` 할 때 추가되지 않도록 코드 추가

## 230424
- `user_page` 로 가는 버튼 추가

## 230425
- `작성글 수정` 함수 수정

## 230426
- `수정` 함수 테스트 : 성공

## 230427
- `수정하기` 에서 `수정할 글` 을 보러 돌아가는 버튼 생성

## 230428
- `버튼` 작동 테스트 : 코드 수정 후 성공 (local variable 위치 변경)

## 230429
- 로그인하지 않은 유저가 글을 수정하지 못하도록 코드 수정

## 230439
- `detail` 페이지 로그인 여부에 따라서 구분한 코드 리팩토링

## 230501
- 로그인 여부에 따른 `index` 페이지 구분(public or not) 코드 html에서 구현하고, `index_auth.html` 삭제

## 230502
- `detail` 페이지를 하나로 결정. 대신 로그인한 유저만 볼 수 있도록 변경
- 로그인한 유저만 `article` 을 `삭제` 할 수 있도록 코드 변경

## 230503
- `user_page` 좋아요 table에 결제 버튼 생성

## 230504
- `detail` 페이지, `user_page` 페이지 실행 테스트 및 코드 수정

## 230615
- `index` 페이지에 현재 로그인한 유저명 표시
- `user_page` 좋아요한 글, 작성한 글이 표시되지 않는 오류 해결

## 230616
- `현재 로그인한 user`가 `좋아요` 한 글이 이미 `user_page` 에 있으면 추가되지 않도록 코드 수정

## 230617
- `user_page` 에 `좋아요 취소` 기능 추가

## 230619
- `새로운 기능`의 `view`, `url`, `버튼` 추가

## 230620
- `static` 경로 설정
- `axios` 기본 설정

## 230621
- `axios` 전송 테스트

## 230622
- `새로운 기능` 작동 버튼에 `axios` 전송 함수 적용

## 230623
- `axios` 요청 방식을 `post` 로 변경

## 230624
- `기능` 버튼을 누르면 서버에서 처리된 `text` 가 템플릿에 추가되는 기능 추가

## 230625
- `기능` 버튼을 누르면 페이지의 `content` 를 서버로 보내는 기능 구현

## 230627
- `처리된 text` 의 `style` 속성 추가

## 230628
- `처리된 text` 의 `위치` 변경

## 230629
- `기능` 버튼 누를 시 페이지의 `내용` 서버로 전송 기능 추가
- `기능` 버튼 누르면 속성 부여 동작 추가

## 230630
- `기능` 버튼 클릭할 때마다 속성 부여된 `요소` 추가되는 동작 추가

## 230701
- 추가되는 `요소` 의 스타일 변경

## 230702
- 받은 `content` 를 `list` 형식으로 바꿔서 템플릿 변수로 전달

## 230703
- 템플릿 변수에 전달된 `conent` 가 요소를 분리해서 추가되는 기능 추가

## 230704
- 요소에 `배경색` 과 `그림자` 추가

## 230705
- 서버에서 받은 문장 `content` 분할해서 요소로 추가하는 기능 구현

## 230706
- `openai` 를 사용해 `content` 에서 `명사` 만 추출

## 230707
- 라이브러리 import 및 `openai` 호출 방식 변경

## 230710
- `맞춤법 검사` 및 교정 기능 추가

## 230711
- `keyword 추출` 기능과 `맞춤법 검사` 기능 페이지 표시 영역 및 버튼 분리

## 230712
- 분리한 두 버튼 동작 확인

## 230713
- 버튼 클릭시 페이지에 내용이 나오도록 코드 수정

## 230714
- `맞춤법 검사` 결과에 스타일 적용

## 230715
- `keyword 추출` 코드 작성

## 230717
- `keword 추출` 후 처리된 텍스트가 페이지에 표시되는 동작 구현

## 230718
- `keyword 추출 과정` 개선 : 명사형 품사만 추출

## 230719
- `keyword 추출 과정` 개선 : 최빈 단어만 추출

## 230720
- `기능` 으로 추가된 요소들이 표시되는 방법 개선 : 줄바꿈시 상하로 겹치는 현상 해결

## 230721
- `기능` 버튼들의 `클릭` 동작이 한 번만 작동하도록 수정

## 230723
- `버튼` 클릭 시 맞춤법 교정된 단어로 페이지의 글이 수정되는 기능 추가

## 230731
- `로그인 필요` modal 내용 추가

## 230801
- `로그인 필요` modal 링크 추가 및 디자인 수정

## 230802
- `AWS IAM` 세팅을 위해 필요한 코드 추가

## 230803
- `AWS RDS` 세팅을 위해 필요한 코드 추가

## 230804
- `AWS Beanstalk`, `Github actions` 사용을 위해 필요한 코드 추가

## 230805
- `맞춤법 검사` 된 텍스트로 `content` 내용 바꾸는 버튼 업데이트

## 230809
- `영문` `키워드 추출`, `맞춤법 교정` 기능 추가
- `content` 가 한글인 경우와 영문인 경우 구분

## 230810
- `맞춤법 교정` 버튼에 `click` 효과 부여