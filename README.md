<!DOCTYPE html>
<html lang="ar" dir="rtl">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>formulaire systéme solaire</title>
</head>
<body style="background-color:#b356ff; color:aliceblue">
    <h1>ملأ استمارة تسجيل :</h1>
    <form>
        <label for="nom">الاسم</label>
        <input type="text" id="nom" name="nom" required>
        <br><br>
        <label for="email">الايمايل</label>
        <input type="email" id="email" name="email" required>
        <br><br>
        <label for="password">كلملة السر</label>
        <input type="redio" id="password" name="password" required minlength="6">
        <br><br>
        <label>الجنس:</label>
        <input type="radio" id="male" name="gender" value="male">
        <label for="male">Male</label>
        <input type="radio" id="female" name="gender" value="female">
        <label for="female">Female</label>
        <br><br>
        <ol>
        <label> ماهو كوكبك المفضل؟</label></ol>
        <input type="checkbox" id="الشمس" name="planet" value="planet">
        <label for="name of the planet">الشمس</label><br>
        <input type="checkbox" id="عطارد" name="planet" value="planet">
        <label for="name of the planet">عطارد</label><br>
        <input type="checkbox" id="المريخ" name="planet" value="planet">
        <label for="name of the planet">المريخ</label><br>
        <input type="checkbox" id="زحل" name="planet" value="planet">
        <label for="name of the planet">زحل</label><br>
        <input type="checkbox" id="الأرض" name="planet" value="planet">
        <label for="name of the planet">الأرض</label><br>
        <br><br>
        <button style="color: beige;color:black" type="submit">ارسال</button>

    </form>
    
</body>
</html>
