<!DOCTYPE html>

<html>

<head>

<title>تسجيل حساب جديد</title>

<meta charset=”UTF-8″>

<meta name=”viewport” content=”width=device-width, initial-scale=1.0″>

<style>

body {

font-family: Arial, sans-serif;

margin: 0;

padding: 0;

background-color: #f2f2f2;

}

form {

background-color: #fff;

margin: 50px auto;

padding: 20px;

max-width: 500px;

border-radius: 10px;

box-shadow: 0 0 10px rgba(0, 0, 0, 0.2);

}

h1 {

font-size: 36px;

margin-bottom: 20px;

text-align: center;

color: #333;

}

input[type=”text”], input[type=”email”], input[type=”password”] {

display: block;

width: 100%;

margin-bottom: 20px;

padding: 10px;

border: none;

border-radius: 5px;

box-shadow: 0 0 5px rgba(0, 0, 0, 0.2);

font-size: 16px;

color: #333;

font-family: Arial, sans-serif;

}

input[type=”submit”] {

display: block;

width: 100%;

padding: 10px;

border: none;

border-radius: 5px;

background-color: #333;

color: #fff;

font-size: 18px;

cursor: pointer;

transition: background-color 0.3s ease-in-out;

}

input[type=”submit”]:hover {

background-color: #555;

}

</style>

</head>

<body>

<form>

<h1>تسجيل حساب جديد</h1>

<label for=”name”>الاسم:</label>

<input type=”text” id=”name” name=”name” required>

<label for=”email”>البريد الإلكتروني:</label>

<input type=”email” id=”email” name=”email” required>

<label for=”password”>كلمة المرور:</label>

<input type=”password” id=”password” name=”password” required>

<input type=”submit” value=”إنشاء الحساب”>

</form>

</body>

</html>
