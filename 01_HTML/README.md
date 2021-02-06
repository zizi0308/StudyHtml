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

## HTML 입력 태그

```html
<!DOCTYPE html>
<html>
<head>
    <meta charset='utf-8'>
    <meta http-equiv='X-UA-Compatible' content='IE=edge'>
    <title>Page Title</title>
    <meta name='viewport' content='width=device-width, initial-scale=1'>
</head>
<body>
    <form>
        <!-- 사용자가 입력하는 양식 -->
        <input type="text" name="userid" value="personar95"><br>
        <input type="password" name="password" value="12345"><br>
        <input type="file" name="attach_file" value=""><br>
        <input type="checkbox" name="chk_hobby_swim" value="SWIM" >수영<br>
        <input type="checkbox" name="chk_hobby_marathon" value="MARATHON">마라톤<br>
        <input type="radio" name="rdo_gender" value="M">남자
        <input type="radio" name="rdo_gender" value="F">여자
        <input type="radio" name="rdo_gender" value="G">중성<br>
        <!-- <input type="datetime" name="dt_today" value="2021-01-28 14:50:00"><br> -->

        <!-- 보이지 않은 양식-->
        <input type="hidden" name="hdn_temp_val" value="25685945871DF"><br>

        <!-- 버튼 -->
        <input type="button" name="btn_normal" value="Click"><br>
        <input type="reset" name="btn_reset" value="Reset"><br>
        <input type="submit" name="btn_reset" value="제출"><br>

        <!-- 기타 -->
        <input type="image" src="https://placehold.it/400x250"><br>

        <!-- 선택컨트롤(콤보박스/드랍다운) -->
        <select>
            <option>김밥</option>
            <option>떡복이</option>
            <option>순대</option>
            <option selected>오뎅</option>
        </select>
    </form>    
</body>
</html>
```



### 결과 이미지
![결과](https://blogfiles.pstatic.net/MjAyMTAyMDZfMzkg/MDAxNjEyNjAzMjA1ODE5.LBDuQ6DH0C92rUDwGWqz4JSzTRWThQBX3q2ki4Ps7vYg.4V4EDTC6PDCFoSwC2_zbWi0f0x2424hbtxRrBIz3R_Ig.PNG.whgmlwl222/form_practice_result_01.png)


-


[이전](https://github.com/zizi0308/StudyHtml)
