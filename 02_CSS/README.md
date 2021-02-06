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

#### 

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


