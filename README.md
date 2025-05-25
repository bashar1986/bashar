<!DOCTYPE html>
<html lang="ar" dir="rtl">
<head>
    <meta charset="UTF-8">
    <title>نظام إدارة الميناء /اعداد بشار جارالله </title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #e6f2ff;
            margin: 0;
            padding: 0;
        }
        .header {
            background-color: #004080;
            color: white;
            padding: 20px;
            text-align: center;
        }
        .nav {
            background-color: #0066cc;
            overflow: hidden;
            padding: 10px;
        }
        .nav a {
            color: white;
            text-align: center;
            padding: 10px 15px;
            text-decoration: none;
            font-size: 17px;
        }
        .nav a:hover {
            background-color: #0052a3;
        }
        .container {
            margin: 20px;
        }
        .section {
            background-color: white;
            margin-bottom: 20px;
            padding: 20px;
            border-radius: 5px;
            box-shadow: 0 0 5px rgba(0,0,0,0.1);
        }
        .footer {
            background-color: #004080;
            color: white;
            text-align: center;
            padding: 10px;
            position: fixed;
            bottom: 0;
            width: 100%;
        }
        table {
            width: 100%;
            border-collapse: collapse;
        }
        table, th, td {
            border: 1px solid #ddd;
        }
        th, td {
            padding: 12px;
            text-align: right;
        }
        th {
            background-color: #0066cc;
            color: white;
        }
        tr:nth-child(even) {
            background-color: #f2f2f2;
        }
    </style>
</head>
<body style="color: #333;">



    <div class="header">
        <h1>نظام إدارة الميناء  </h1>
        <h2>نظام متكامل لإدارة عمليات الميناء البحري</h2>
        <h3> اعداد الطالب بشار جارالله / قسم علوم الحاسوب</h3>
    </div>
<div class="container">
     <center> <img src="WhatsApp-Image-2023-12-24-at-11.03.30-PM.jpeg"alt= "Test Image"<"width = "750" height = "450""3> </center>

    <div class="nav">
        <a href="#ships">إدارة السفن</a>
        <a href="#containers">إدارة الحاويات</a>
        <a href="#employees">إدارة الموظفين</a>
        <a href="#reports">التقارير</a>
    </div>

    <div class="container">
        <div id="ships" class="section">
            <center><h2 style="color: #004080;">إدارة السفن</h2></center>
            <hr>
            
            <p><b>السفن الحالية في الميناء:</b></p>
            
            <table>
                <tr>
                    <th>اسم السفينة</th>
                    <th>نوع السفينة</th>
                    <th>الحمولة (طن)</th>
                    <th>تاريخ الوصول</th>
                    <th>الحالة</th>
                </tr>
                <tr>
                    <td>سفينة الخليج</td>
                    <td>ناقلة بضائع</td>
                    <td>50,000</td>
                    <td>2023-05-6</td>
                    <td><u>قيد التفريغ</u></td>
                </tr>
                <tr>
                    <td>بحر العرب</td>
                    <td>حاويات</td>
                    <td>75,000</td>
                    <td>2025-05-1</td>
                    <td><b>تم التفريغ</b></td>
                </tr>
                <tr>
                    <td>النجم الساطع</td>
                    <td>ناقلة نفط</td>
                    <td>120,000</td>
                    <td>2025-05-10</td>
                    <td>في الانتظار</td>
                </tr>
            </table>
            
            <p style="margin-top: 20px;"><small>تاريخ آخر تحديث: 2023-05-20</small></p>
        </div>

        <div id="containers" class="section">
            <center><h2 style="color: #004080;">إدارة الحاويات</h2></center>
            <hr>
            
            <p><big>إحصائيات الحاويات:</big></p>
            
            <table bgcolor="#f9f9f9">
                <tr>
                    <td colspan="3"><center><b>إحصائية الحاويات</b></center></td>
                </tr>
                <tr>
                    <td>إجمالي الحاويات</td>
                    <td>1,250</td>
                    <td>حاوية</td>
                </tr>
                <tr>
                    <td>الحاويات الفارغة</td>
                    <td>320</td>
                    <td>حاوية</td>
                </tr>
                <tr>
                    <td>الحاويات المحملة</td>
                    <td>930</td>
                    <td>حاوية</td>
                </tr>
            </table>
            
            <p>أنواع الحاويات:</p>
            <ul>
                <li>حاويات 20 قدم</li>
                <li>حاويات 40 قدم</li>
                <li>حاويات مبردة</li>
                <li>حاويات ذات حجم خاص</li>
            </ul>
        </div>

        <div id="employees" class="section">
            <center><h2 style="color: #004080;">إدارة الموظفين</h2></center>
            <hr>
            
            <p><u>طاقم العمل الحالي:</u></p>
            
            <table>
                <tr>
                    <th>الاسم</th>
                    <th>الوظيفة</th>
                    <th>المناوبة</th>
                    <th>تاريخ التعيين</th>
                </tr>
                <tr>
                    <td>أحمد ناطق</td>
                    <td>مشغل رافعة شوكية<sup></sup></td>
                    <td>صباحية</td>
                    <td>2020-03-15</td>
                </tr>
                <tr>
                    <td>حسين محمود</td>
                    <td>مشرف ميناء</td>
                    <td>مسائية</td>
                    <td>2018-06-22</td>
                </tr>
                <tr>
                    <td>محمود ماهر</td>
                    <td>موظف استقبال</td>
                    <td>صباحية</td>
                    <td>2021-01-10</td>
                </tr>
            </table>
            
            
        </div>

        <div id="reports" class="section">
            <center><h2 style="color: #004080;">التقارير</h2></center>
            <hr>
            
            <p><b>تقارير الميناء الشهرية:</b></p>
            
            <table>
                <tr>
                    <th>الشهر</th>
                    <th>عدد السفن</th>
                    <th>عدد الحاويات</th>
                    <th>الإيرادات (دولار)</th>
                </tr>
                <tr>
                    <td>يناير 2025</td>
                    <td>45</td>
                    <td>1,200</td>
                    <td>2,450,000</td>
                </tr>
                <tr>
                    <td>فبراير 2025</td>
                    <td>52</td>
                    <td>1,350</td>
                    <td>2,800,000</td>
                </tr>
                <tr>
                    <td>مايو 2025</td>
                    <td>38</td>
                    <td>980</td>
                    <td>2,100,000</td>
                </tr>
            </table>
<!-- روابط المواقع -->
  <table width="90%" align="center" bgcolor="#ffffff" cellpadding="20" border="1" bordercolor="#b3e5fc">
    <tr>
      <td>
        <a name="sites"></a>
        <h2><font face="Tahoma" color="#006064">روابط مواقع إلكترونية مشهورة</font></h2>
        <ul>
  
          
 <li><a href="https://www.gcpi.gov.iq/" target="_blank">الموقع الالكتروني للشركة العامة لموانئ العراق </a></li>
    <li><a href="https://uomosul.edu.iq/computerscience/" target="_blank">الموقع الالكتروني لكلية علوم الحاسوب والرياضيات  </a></li>
<li><a href="https://www.w3schools.com" target="_blank"><font face="Arial">موقع W3Schools لتعلم HTML</font></a></li>
          <li><a href="https://www.github.com" target="_blank"><font face="Arial">موقع GitHub للمشاريع البرمجية</font></a></li>
        </ul>
      </td>
    </tr>
  </table>
            
            <p style="margin-top: 20px;">
                <sub>ملاحظة: جميع البيانات تعكس الحالة حتى نهاية الشهر</sub>
            </p>
        </div>
    </div>

    <div class="footer">
        <p>نظام إدارة الميناء البحري &copy; 2025 | تم التطوير بواسطة المبرمج بشار جارالله   </p>
    </div>
</body>
</html>
