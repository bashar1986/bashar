<!DOCTYPE html>
<html lang="ar" dir="rtl">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>بشار جارالله</title>

  <!-- Google Fonts -->
  <link href="https://fonts.googleapis.com/css2?family=Cairo:wght@400;700&display=swap" rel="stylesheet">

  <!-- Font Awesome Icons -->
  <script src="https://kit.fontawesome.com/a076d05399.js" crossorigin="anonymous"></script>

  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
      scroll-behavior: smooth;
    }

    body {
      font-family: 'Cairo', sans-serif;
      background: #f2f2f2;
      color: #333;
    }

    /* Navbar */
    nav {
      background-color: #1e1e2f;
      color: white;
      padding: 15px 30px;
      position: sticky;
      top: 0;
      z-index: 1000;
      display: flex;
      justify-content: space-between;
      align-items: center;
    }

    nav h1 {
      font-size: 1.6em;
      color: #00c9a7;
    }

    nav ul {
      list-style: none;
      display: flex;
      gap: 20px;
    }

    nav ul li a {
      color: white;
      text-decoration: none;
      font-weight: bold;
      transition: 0.3s;
    }

    nav ul li a:hover {
      color: #00c9a7;
    }

    /* Header */
    header {
      background: linear-gradient(to left, #00c9a7, #005b96);
      color: white;
      text-align: center;
      padding: 60px 20px;
    }

    header img {
      width: 150px;
      height: 150px;
      border-radius: 50%;
      border: 5px solid white;
      margin-bottom: 20px;
      box-shadow: 0 4px 10px rgba(0,0,0,0.3);
    }

    header h2 {
      font-size: 2.2em;
      margin-bottom: 10px;
    }

    header p {
      font-size: 1.1em;
    }

    section {
      padding: 60px 20px;
      max-width: 1000px;
      margin: auto;
    }

    section h3 {
      text-align: center;
      color: #005b96;
      margin-bottom: 40px;
      font-size: 2em;
    }

    /* About */
    .about p {
      font-size: 1.1em;
      line-height: 2;
      text-align: center;
      max-width: 800px;
      margin: auto;
    }

    /* Skills */
    .skills {
      display: flex;
      flex-wrap: wrap;
      justify-content: center;
      gap: 20px;
    }

    .skill-box {
      background-color: white;
      padding: 20px;
      border-radius: 10px;
      width: 180px;
      text-align: center;
      box-shadow: 0 2px 10px rgba(0,0,0,0.1);
      transition: 0.3s;
    }

    .skill-box:hover {
      transform: scale(1.05);
    }

    .skill-box i {
      font-size: 2em;
      color: #00c9a7;
      margin-bottom: 10px;
    }

    /* Projects */
    .projects {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
      gap: 20px;
    }

    .project {
      background: white;
      padding: 20px;
      border-radius: 10px;
      box-shadow: 0 2px 10px rgba(0,0,0,0.1);
    }

    .project img {
      width: 100%;
      border-radius: 8px;
      margin-bottom: 10px;
    }

    .project h4 {
      margin-bottom: 5px;
    }

    /* Contact */
    .contact {
      text-align: center;
    }

    .contact a {
      display: inline-block;
      margin: 10px;
      font-size: 1.5em;
      color: #005b96;
      text-decoration: none;
    }

    .contact a:hover {
      color: #00c9a7;
    }

    /* Footer */
    footer {
      background: #1e1e2f;
      color: white;
      text-align: center;
      padding: 20px;
    }

    @media (max-width: 600px) {
      nav ul {
        flex-direction: column;
        align-items: flex-start;
      }
    }
  </style>
</head>

<body>

  <!-- Navbar -->
  <nav>
    <h1>بشار جارالله</h1>
    <ul>
      <li><a href="#about">عني</a></li>
      <li><a href="#skills">مهاراتي</a></li>
      <li><a href="#projects">مشاريعي</a></li>
      <li><a href="#contact">تواصل</a></li>
    </ul>
  </nav>

  <!-- Header -->
  <header>
    <img src="https://via.placeholder.com/150" alt="صورة بشار" />
    <h2>بشار جارالله</h2>
    <p>مطور ويب ومصمم واجهات - عاشق للتقنية والإبداع</p>
  </header>

  <!-- About -->
  <section id="about" class="about">
    <h3>من أنا؟</h3>
    <p>
      أنا بشار، شغوف بعالم البرمجة وتصميم الويب. أعمل على بناء مواقع عصرية وجذابة باستخدام أحدث التقنيات. أحب التحديات واستكشاف كل جديد في عالم التقنية.
    </p>
  </section>

  <!-- Skills -->
  <section id="skills">
    <h3>مهاراتي</h3>
    <div class="skills">
      <div class="skill-box">
        <i class="fab fa-html5"></i>
        <p>HTML5</p>
      </div>
      <div class="skill-box">
        <i class="fab fa-css3-alt"></i>
        <p>CSS3</p>
      </div>
      <div class="skill-box">
        <i class="fab fa-js-square"></i>
        <p>JavaScript</p>
      </div>
      <div class="skill-box">
        <i class="fab fa-react"></i>
        <p>React</p>
      </div>
      <div class="skill-box">
        <i class="fab fa-node-js"></i>
        <p>Node.js</p>
      </div>
      <div class="skill-box">
        <i class="fab fa-github"></i>
        <p>GitHub</p>
      </div>
    </div>
  </section>

  <!-- Projects -->
  <section id="projects">
    <h3>مشاريعي</h3>
    <div class="projects">
      <div class="project">
        <img src="https://via.placeholder.com/300x200" alt="مشروع 1" />
        <h4>موقع شخصي</h4>
        <p>تصميم وتطوير موقع شخصي بتقنية HTML/CSS/JS.</p>
      </div>
      <div class="project">
        <img src="https://via.placeholder.com/300x200" alt="مشروع 2" />
        <h4>لوحة تحكم</h4>
        <p>بناء لوحة تحكم ديناميكية باستخدام React.</p>
      </div>
      <div class="project">
        <img src="https://via.placeholder.com/300x200" alt="مشروع 3" />
        <h4>تطبيق إدارة مهام</h4>
        <p>تطبيق ويب بسيط لإدارة المهام باستخدام Node.js وMongoDB.</p>
      </div>
    </div>
  </section>

  <!-- Contact -->
  <section id="contact" class="contact">
    <h3>تواصل معي</h3>
    <a href="#"><i class="fab fa-twitter"></i></a>
    <a href="#"><i class="fab fa-linkedin"></i></a>
    <a href="#"><i class="fab fa-github"></i></a>
    <a href="mailto:you@example.com"><i class="fas fa-envelope"></i></a>
  </section>

  <!-- Footer -->
  <footer>
