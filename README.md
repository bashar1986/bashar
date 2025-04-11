<!DOCTYPE html>

<html>

<head>

  <title>نموذج شراء المنتج</title>

</head>

<body>

  <form>

    <label for="fname">الاسم الأول:</label><br>

    <input type="text" id="fname" name="fname"><br>

    <label for="lname">اسم العائلة:</label><br>

    <input type="text" id="lname" name="lname"><br><br>

    <label for="address">العنوان:</label><br>

    <input type="text" id="address" name="address"><br><br>

    <label for="state">اختر المحافظة:</label><br>

    <select name="state" id="state">

      <option value="">--اختر المحافظة--</option>

      <option value="1">البصرة1</option>

      <option value="2">بغداد2</option>

      <option value="3">موصل السماقية 3</option>

    </select><br><br>

    <label for="quantity">الكمية:</label><br>

    <input type="number" id="quantity" name="quantity" min="1"><br><br>

    <label for="message">رسالة:</label><br>

    <textarea id="message" name="message"></textarea><br><br>

    <input type="submit" value="إرسال">

  </form>

  <p>التكلفة الإجمالية: <span id="total"></span></p>

  <script>

    // سعر المنتج
    var price = 10;

    // سعر التوصيل لكل محافظة
    var deliveryPrices = {

      "1": 5,

      "2": 7,

      "3": 10

    };

    // حساب التكلفة الإجمالية
    function calculateTotal() {

      var quantity = document.getElementById("quantity").value;

      var state = document.getElementById("state").value;

      var deliveryPrice = deliveryPrices[state];

      var total = (price * quantity) + deliveryPrice;

      document.getElementById("total").textContent = total;

    }

    // إضافة مستمع للحدث على حقول الإدخال
    document.getElementById("quantity").addEventListener("input", calculateTotal);

    document.getElementById("state").addEventListener("change", calculateTotal);

  </script>

</body>

<
