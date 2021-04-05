## Bootstrap 

**잠깐!!** bootstrap 사용하기 전 **준비과정**

> 기존의 html head에 아래 코드 입력

```html
<!-- 합쳐지고 최소화된 최신 CSS -->
<link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.2/css/bootstrap.min.css">

<!-- 부가적인 테마 -->
<link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.2/css/bootstrap-theme.min.css">

<!-- 합쳐지고 최소화된 최신 자바스크립트 -->
<script src="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.2/js/bootstrap.min.js"></script>
```

> => live server 창에서 F12 -> network -> 새로고침 -> iquery code 필요 오류

<script   src="https://code.jquery.com/jquery-3.6.0.js"   integrity="sha256-H+K7U5CnXl1h5ywQfKtSj8PCmoN9aaq30gDh27Xc0jk="   crossorigin="anonymous"></script> 

> -> 위의 코드 head 에 입력

**bootstrap 활용**

* 콘테이너

  ```html
  <div class="container">
    ...
  </div>
  ```

* 버튼

  ```html
  <button type="button" class="btn btn-primary">Primary</button>
  ```

* 이메일 주소, 암호 

  ```html
  <form>
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
    <button type="submit" class="btn btn-default">제출</button>
  </form>
  ```

* 네비게이션 창

  탭형 

  ```html
  <ul class="nav nav-tabs">
    <li role="presentation" class="active"><a href="#">Home</a></li>
    <li role="presentation"><a href="#">Profile</a></li>
    <li role="presentation"><a href="#">Messages</a></li>
  </ul>
  ```
 
  --> <a href="./index.html">Bootstrap 실습 링크</a>
