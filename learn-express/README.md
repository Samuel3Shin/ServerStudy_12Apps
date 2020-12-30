# express로 웹 서버 만들기

express는 http 모듈의 요청과 응답 객체에 추가 기능들을 부여한 모듈이다.
거의 모든 Node.js 서버는 express 모듈로 만들어진다. 그냥 믿고 쓰면 된다.

미들웨어가 express의 핵심이다.
미들웨어는 요청과 응답의 중간(middle)에 위치하여 미들웨어라고 부른다.
미들웨어는 요청과 응답을 조작하여 기능을 추가하기도 하고, 나쁜 요청을 걸러내기도 한다.
미들웨어는 req, res, next를 매개변수로 가지는 함수로서 app.use나 app.get, app.post 등으로 장착한다.
특정한 주소의 요청에만 미들웨어가 실행되게 하려면 첫 번째 인수로 주소를 넣으면 된다.

nodemon 모듈: 서버 코드를 수정할 때마다 서버를 자동으로 재시작해준다.

실행 명령어 <br>
$ npm install <br>
$ node app.js <br>