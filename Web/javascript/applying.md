# 자바스크립트 적용

## 내부 자바 스크립트 코드
\<script> 태그를 이용해 HTML 문서 안에 삽입할 수 있다.

```javascript
<script>
    document.getElementById("text").innerHTML="반갑습니다.";
</script>
```

예)
```html
<!DOCTYPE html>
<html>
<head>
    <meta charset="UTF-8">
    <script>
        function ChangeText(){
            document.getElementById("text").innerHTML="반갑습니다.";
        }
    </script>
</head>
<body>
    <p id = "text">안녕하세요.</p>
    <button onclick=ChangeText()>클릭</button>
</body>
</html>
```
<!DOCTYPE html>
<html>
    <head>
        <meta charset="UTF-8">
        <script>
            function ChangeText(){
                document.getElementById("text").innerHTML="반갑습니다.";
            }
        </script>
    </head>
    <body>
        <p id = "text">안녕하세요.</p>
        <button onclick=ChangeText()>클릭</button>
    </body>
</html>

# 외부 자바스크립트 파일 적용
```html
<!DOCTYPE html>
<html>
<head>
    <meta charset="UTF-8">
    <script src=/js/test.js></script>
</head>
<body>
    <p id = "text">안녕하세요.</p>
    <button onclick=ChangeText()>클릭</button>
</body>
</html>
```
#
출처

http://tcpschool.com/javascript/js_intro_apply
#
