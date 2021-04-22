### Bootstrap

---

Css/JavaScript 기반 웹 프레임워크

단, 티가나고 성능이 다소 떨어짐

※ 사용시 code.jquery.com에서 긁어오기 

http://bootstrapk.com/getting-started/

---



```html
<!DOCTYPE html>
<html lang="ko">
    <head>
        <script
  src="https://code.jquery.com/jquery-3.6.0.js"
  integrity="sha256-H+K7U5CnXl1h5ywQfKtSj8PCmoN9aaq30gDh27Xc0jk="
  crossorigin="anonymous"></script>
        <!-- 합쳐지고 최소화된 최신 CSS -->
<link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.2/css/bootstrap.min.css">

<!-- 부가적인 테마 -->
<link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.2/css/bootstrap-theme.min.css">

<!-- 합쳐지고 최소화된 최신 자바스크립트 -->
<script src="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.2/js/bootstrap.min.js"></script>
        <meta charset="utf-8"> 
        <title>나를 소개해요</title>
    </head>

    <body>
        <div class="container">
            <br>
            <ul class="nav nav-tabs">
                <li role="presentation" class="active"><a href="1.html">유년기</a></li>
                <li role="presentation"><a href="2.html">질풍노도의 시기</a></li>
                <li role="presentation"><a href="3.html">방황기</a></li>
                <li role="presentation"><a href="4.html">지금</a></li>
              </ul>

        <h1>임채호를 소개해요 </h1>
        <h2> 임채호를 소개해요 </h2>
            <br>
            <form action="전송받을 대상">
                아이디 : <input type="text" name="id">
            비밀번호 : <input type="password" name="pw">
                <div class="form-group">
                  <label for="exampleInputEmail1">이메일 주소</label>
                  <input type="email" class="form-control" id="exampleInputEmail1" placeholder="이메일을 입력하세요">
                </div>
                <div class="form-group">
                  <label for="exampleInputPassword1">암호</label>
                  <input type="password" class="form-control" id="exampleInputPassword1" placeholder="암호">
                </div>
                <div class="form-group">
                  <label for="exampleInputFile">파일 업로드</label>
                  <input type="file" id="exampleInputFile">
                  <p class="help-block">여기에 블록레벨 도움말 예제</p>
                </div>
                <div class="checkbox">
                  <label>
                    <input type="checkbox"> 입력을 기억합니다
                  </label>
                </div>
                <input type="submit" class="btn btn-primary">
              </form>

              <br>
        <br>

        <img src="snowman.jpg" height="300" width="300">
        <br>

        <form action="전송받을 대상">

            <h2>나의 일기장</h2>
            제목 : <input type="text" name="diarytitle"> <br>
            <select>
                <option value="goodday"> 좋은날 </option>
                <option value="sadday"> 슬픈날 </option>
                <option value="soso"> 그냥그런날 </option>
            </select> <br>

            내용 : <br>
            <textarea cols="38" rows="20"> </textarea>
            <br> <input type="submit">
        </form> <br>

        <h2> 나의 일대기</h2>
        <ol>
            <li><a href="1.html"> 유년기</a> </li>
            <li><a href= "2.html"> 질풍노도의 시기</a></li>
            <li><a href = "3.html">방황기</a> </li>
            <li><a href = "4.html">지금</a> </li>
        </ol>

    </div>
    </body>
</html>

```

