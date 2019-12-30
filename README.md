# logintest 

<code>git clone https://github.com/TaeKyoungKim/logintest </code><br>
<code>npm install </code>

#### app.js에서 express 라이브러리 활용
<code> app.set()</code><br>
<code>app.use()</code><br>
<code> app.liten()</code><br>

#### rotuer 폴더에 라우팅 파일 작성

<code> var router = express.Router()</code><br>
<code>  rouer.get()</code><br>
<code>  rouer.route().post</code><br>

#### app.js에 라우팅 파일 임포트
<code>  require('라우팅 파일 경로')</code><br>
<code>  app.use('요청경로', require('라우팅 파일 경로'))</code><br>


#### <code>node app.js </code>
