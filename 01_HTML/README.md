# HTML 기본학습

## 웹페이지 기본구조와 작성방법
태그, 요소, 속성의 의미이해 및 HTML, CSS, JS 작성방법 알아보기

## HTML 기본 태그

```html
<!DOCTYPE html>
<html>
<head>
    <title>HTML5+CSS3 Text</title>
</head>
<body>
    <h1>제목 글자태그1</h1>
    <h2>제목 글자태그2</h2>
    <h3>Heading 3</h3>
    <h4>Heading 4</h4>
    <p> 문장</p>
    <h5>Heading 5</h5>
    <h6>Heading 6</h6>
</body>
</html>
```

-

## HTML 입력 태그 및 스타일태그 

```html
<!DOCTYPE html>
<html>
<head>
    <meta charset='utf-8'>
    <meta http-equiv='X-UA-Compatible' content='IE=edge'>
    <title>폼 연습</title>
    <meta name='viewport' content='width=device-width, initial-scale=1'>
</head>
<style>
    h1 {
        color: teal;
        background-color: yellow;
    }
</style>


<body>
    <h1>Welcome!</h1>
    <form>
        <label for="txt_userid">아이디</label>
        <input type="text" name="txt_userid" value="zizi0308"><br>
        <label>비밀번호</label>
        <input type="password" name="password" value="zizi0308"><br>
        <input type="checkbox" name="txt_userid" value="0">
        <label for="checkbox">아이디 자동저장</label><br>
        <input type="button" name="log-in" value="log-in">
    </form>
    <br>
    <form>
        <label for="name">이름</label>
        <input id="name" type="text"><br>
    
        <label for="birth_date">생년월일</label>
        <select>
            <option selected>년도</option>
        </select>
        <select>
            <option selected>월</option>
            <option>1</option>
            <option>2</option>
            <option>3</option>
            <option>4</option>
            <option>5</option>
            <option>6</option>
            <option>7</option>
            <option>8</option>
            <option>9</option>
            <option>10</option>
            <option>11</option>
            <option>12</option>
        </select>
        <select>
            <option selected>일</option>
        </select>
        <br>

        <label for="gender">성별</label>
        <input type="radio" name="rdo_button"><label for="gender">남</label>
        <input type="radio" name="rdo_button"><label for="gender">여</label>

        
    </form>
    ```


### 결과 이미지


![결과](https://blogfiles.pstatic.net/MjAyMTAyMDZfMzkg/MDAxNjEyNjAzMjA1ODE5.LBDuQ6DH0C92rUDwGWqz4JSzTRWThQBX3q2ki4Ps7vYg.4V4EDTC6PDCFoSwC2_zbWi0f0x2424hbtxRrBIz3R_Ig.PNG.whgmlwl222/form_practice_result_01.png)


-

## HTML 구조화 태그

```html
<!DOCTYPE html>
<html>
<head>
    <meta charset='utf-8'>
    <meta http-equiv='X-UA-Compatible' content='IE=edge'>
    <title>공간분할 페이지</title>
    <meta name='viewport' content='width=device-width, initial-scale=1'>
    <link rel='stylesheet' type='text/css' media='screen' href='main.css'>
    <script src='main.js'></script>
</head>
<body>
    <header>
        <h1>공간분할 테스트</h1>
    </header>
    <nav>
        <ul>
            <li><a href="#">메뉴 1</a></li>
            <li><a href="#">메뉴 2</a></li>
            <li><a href="#">메뉴 3</a></li>
            <li><a href="#">메뉴 4</a></li>
        </ul>
    </nav>
    <section>
        <article>
            <h2>Lorem ipsum dolor sit amet</h2>
            <p> consectetur adipisicing elit. Ad nulla aut temporibus minus ducimus eius ab in mollitia obcaecati labore recusandae expedita, maiores eos quaerat a cumque. Vero, rem minus?</p>
        </article>
        <article>
            <h3>Lorem ipsum dolor sit amet</h3>
            <p> consectetur adipisicing elit. Ad nulla aut temporibus minus ducimus eius ab in mollitia obcaecati labore recusandae expedita, maiores eos quaerat a cumque. Vero, rem minus?</p>
        </article>
    </section>
    <footer>
        <address>부산광역시 남구 용호동 부경대학교 용당캠퍼스</address>
    </footer>
</body>
</html>
```

### 결과 이미지

![결과](https://blogfiles.pstatic.net/MjAyMTAyMDZfMjQ0/MDAxNjEyNjA0NDUwNTg3.2PWCMaM4VWM1WhEF-5YbgjtGSvPYIfS-ZT_BHyAyiMog.KoYYdUJnt1vaBhJ2cRCA_YozcWzb0C1jKS5b7U5W0Vcg.PNG.whgmlwl222/space_practice.png)


-


[이전](https://github.com/zizi0308/StudyHtml)
