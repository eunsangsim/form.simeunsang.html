# form.simeunsang.html
<!DOCTYPE html>
<html lang="ko">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>간단한 입력 폼</title>
</head>
<body>
    <h1>사용자 정보 입력</h1>
    <form>
        <label for="name">이름:</label>
        <input type="text" id="name" name="name" value=""><br><br>
        <label for="password">암호:</label>
        <input type="password" id="password" name="password" value="" maxlength="4"><br><br>
        <h3>받고싶은 선물을 고르시오</h3>
        <hr>
        <input type="radio" id="science" name="subject" value="1">
        <label for="science">후드티</label><br>
        <input type="radio" id="math" name="subject" value="2" checked>
        <label for="math">립스틱</label><br>
        <input type="radio" id="english" name="subject" value="3">
        <label for="english">팬티</label><br><br>
        <h3>먹고 싶은 것 모두 체크하세요</h3>
        <hr>
        <input type="checkbox" id="jjajang" name="food" value="1">
        <label for="jjajang">짜장면</label><br>
        <input type="checkbox" id="chicken" name="food" value="2" checked>
        <label for="chicken">닭강정</label><br>
        <input type="checkbox" id="tteokbokki" name="food" value="3">
        <label for="tteokbokki">엽기떡볶이</label><br><br>
        <input type="submit" value="제출">
    </form>

</body>
</html>
