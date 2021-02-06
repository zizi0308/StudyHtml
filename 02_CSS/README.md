# CSS3 기본학습

## CSS3 기본구조와 작성방법
CSS 블록생성 및 선택자의 이해와 선택자 활용

## CSS3 선택자 용도와 사용법

### 전체선택자와 태그선택자


```html
<!DOCTYPE html>
<html>

<head>
    <meta charset='utf-8'>
    <meta http-equiv='X-UA-Compatible' content='IE=edge'>
    <title>css Select Basic</title>
    <meta name='viewport' content='width=device-width, initial-scale=1'>
    <style>
       h1 {
           color: blue;
           font-family: dotum;
       }
        p {
            color: red;
            background-color: yellowgreen;
        }
    </style>
</head>

<body>
    <h1>제목입니다</h1>
    <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Officiis adipisci sed dolorum architecto repellat aut
        nam id eveniet ea debitis, alias cupiditate, soluta amet repudiandae quae earum ex, quod nesciunt!</p>

    <h2>서브제목 입니다</h2>
    <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Vel quibusdam, necessitatibus facere odit consequatur
        eius fugiat aspernatur provident eveniet consequuntur pariatur autem explicabo quisquam voluptatem illum
        accusamus doloremque vero esse.</p>
</body>

</html>
```

#### 결과 이미지

![결과](https://blogfiles.pstatic.net/MjAyMTAyMDZfODIg/MDAxNjEyNjA3MTg5ODQz.tjHhYXv5FOzcZwwzFm5jyou07eaSIWpyDFZxcVPvvsUg.cFtKNVMI8YzmFwE_etOpFFzBYAouznz-7xys6rFEmoYg.PNG.whgmlwl222/select_basic.png)


-


### 자손선택자와 아이디선택자

```html
<!DOCTYPE html>
<html>

<head>
    <meta charset='utf-8'>
    <meta http-equiv='X-UA-Compatible' content='IE=edge'>
    <title>Page Title</title>
    <meta name='viewport' content='width=device-width, initial-scale=1'>
    <style>
        div > h2 {
            color: red;
        }

        #section h2 {
            color: orange;
        }

        h2:hover {
            background-color: black;
        }

        h2:active {
            background-color: blue;
        }

        input:focus {
            background-color: orange;
            }

        input:enabled {
            background-color: greenyellow;
            }
        
        input:disabled {
            background-color: grey;
        }



    </style>
</head>

<body>
    <div id="header">
        <h2 class="title">Lorem ipsum</h2>
        <div id="nav">
            <h2>Navigation</h2>
        </div>
        <div>
            <h3>SubTitle</h3>
        </div>
        <div id="section">
            <h2 class="title">Lorem ipsum</h2>
            <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Ratione velit quos modi dignissimos nemo? Fugiat
                tempore dolor consectetur officiis dignissimos, ab iure quibusdam possimus eius neque et est quasi
                commodi!</p>
        </div>
        <div>
            <form>
                <label for="">이름</label>
                <input name="user_id" type="text" value="zizi0308"><br>
                <label for="">비밀번호</label>
                <input name="user_password" type="text" value="ziz555"><br>
                <input value="disabled" disabled="disabled">
            </form>
        </div>
</body>

</html>
```


#### 자손선택자 결과이미지

![결과](https://blogfiles.pstatic.net/MjAyMTAyMDZfMTE5/MDAxNjEyNjA3MTg5ODMz.w6fbqMsSu5Z7ppixanNZiTeIxcDldBWmCRgBGZlLfN4g._xnSC6dxd_XX5CDLm_UfIvQ2edu0gSz-kdhHEd4glgkg.PNG.whgmlwl222/selector_child.png)


-

```html
<!DOCTYPE html>
<html>
<head>
    <meta charset='utf-8'>
    <meta http-equiv='X-UA-Compatible' content='IE=edge'>
    <title>Page Title</title>
    <meta name='viewport' content='width=device-width, initial-scale=1'>
    <style>
        #header {
            width: 800px;
            height: 300px;
            margin: 0 auto;
            background: coral;
        }

        #wrap {
            width: 800px; 
            margin: 0 auto;
            overflow: hidden;
        }

        #aside {
            width: 300px; 
            float: left;
            background-color: lawngreen;
        }

        #content {
            width: 500px; 
            float: left;
            background-color: whitesmoke;
        }

        #footer {
            width: 800px; 
            margin: 0 auto;
            background-color: cyan;
        }

        .fruits {
            color: red;
            font-weight: bold;
        }

        .item {
            color: salmon;
        }

        .footer {
            background-color: silver;
        }

        input[type="text"] {background: red;}
        
        input[type="password"] {background: blue;}

    </style>
</head>
<body>
    <div id="header"> 
        <h1>#header 태그</h1>
    </div>
    <div id="wrap">
        <div id="aside">
            <h1>#aside 태그</h1>
            <ul>
                <li class="fruits"><a href="https://naver.com">사과</a></li>
                <li><a href="https://microsdft.com">배</a></li>
                <li><a href="https://youtube.com">바나나</a></li>
                <li class="fruits">딸기</li>
            </ul>
        </div>
        <div id="content">
            <h1 class="item footer">#content 태그</h1>
            <form>
                <label>이메일</label>
                <input type="text"><br>
                <label>비밀번호</label>
                <input type="password" name="password" value="zizi0308">
            </form>
        </div>
    </div>
    <div id="footer">
        <h1 class="item footer">#footer 태그</h1>
    </div>
    
</body>
</html>
```

#### 아이디선택자 결과이미지

![결과](https://blogfiles.pstatic.net/MjAyMTAyMDZfMTUx/MDAxNjEyNjA3MTg5ODMz.dhHWSD41fw65kNN_ZFzpGqPwZv64N3IWrsRjVTD0UnYg.jsAAelYHG6xn56cXcToi6jk4DmY1ErTpR6Rc9tfM7Pog.PNG.whgmlwl222/selector_id.png)


-



### 다양한 크기의 단위적응

```html





