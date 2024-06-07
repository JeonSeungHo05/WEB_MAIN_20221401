
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
