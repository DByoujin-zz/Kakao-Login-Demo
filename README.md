## Kakao Devplorer 세팅
1. [여기](https://developers.kakao.com/console/app)에 접속하여, 앱을 추가합니다.
1. 앱설정 -> 플랫폼으로 들어갑니다.
1. Web 플랫폼 등록을 클릭하고, 사이트 주소를 입력합니다.
1. 앱설정 -> 앱 키로 들어가서, JavaScript 키를 복사해둡니다.
1. 제품 설정 -> 카카오 로그인으로 들어가서, 활성화 설정에서 OFF를 ON으로 바꿔줍니다.
1. 제품 설정 -> 동의항목으로 들어가, 순서대로 1, 3, 4, 5, 7를 필수동의 또는 선택동의로 저장해줍니다.

## HTML 파일 세팅
kakao.html를 열고, kakao key 부분을 아까 복사해두었던 JavaScript 키로 변경해줍니다.
```
Kakao.init( "kakao key" );
```