1~4week
기본적인 홈페이지 제작 틀을 재현함 이미지 넣기와 내비게이션 바를 추가함, 화면에 크기에 따라 같이 사이즈가 조정되는 기능을 구현함. 검색기능을 추가함. 표를 만들어 간단한 정보를 넣는 작업을 하였음. 내비게이션바와 이미지에 하이퍼링크를 달아 다른 주소로 갈 수 있도록 하는 기능을 구현함.

5week
팝업창을 구현함 팝업창이 홈체이지에 들어갈 때 화면에 뜨는 것을 구현함 팝업창 화면에 현재 시간과 날짜를 구현함. 이후 시간이 지남에 따라 자동으로 꺼지는 기능을 구현함

7week
자바스크립트 화살표함수를 구현하여 팝업창 함수를 수정함 로그인 화면 구현, 공백체크, 아이디 비밀번호 양식 구현. 로그인 후 홈페이지에 로그인 버튼을 로그아웃 화면으로 바꿈.  오류가 발견되지는 않음. 

10week
팝업창의 쿠키를 저장하는 기능을 구현함.
쿠키가 저장이 안되는 오류를 발견함. pop_up.js의 get.cookie의 closePopup 함수의 cookie 이름이 다른 것을 발견후 'popupYN'으로 이름을 변경 후 오류를 해결함

12week
로그인 하면 로그인 홈페이지로 못들어가는 오류를 발견함
login.js의 get, set Cookie null object 오류를 발견하여 추가해준 후 정상족으로 로그인이 되는 것을 확인함
로그아웃시 세션이 삭제되는 기능이 login.js의 check input()으로 구현이 안되는 것을 확인후 login2로 나뉘어서 로그아웃시 세션 삭제 구현

14week
회원가입을 구현함 회원가입 완료 창을 만듦
회워가입시 세션을 저장하고 가져오는 것을 구현함.
회원가입시 세션을 저장하는 데 암/복호화하는 것을 구현하는 중 기존 session.js의 함수를 가져오는 중 오류를 발견함. 기존 session.js 함수의 sessionStorage.getitem의 이름이 다른 것을 발견 후 수정.
