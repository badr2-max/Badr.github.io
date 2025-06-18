

<!DOCTYPE html>
<html lang="ar" dir="rtl">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>بدر | الصفحة الرسمية</title>

  <!-- خط + CSS Pico -->
  <link rel="stylesheet" href="https://unpkg.com/@picocss/pico">
  <link href="https://fonts.googleapis.com/css2?family=Tajawal&display=swap" rel="stylesheet">

  <!-- أيقونات Font Awesome -->
  <script src="https://kit.fontawesome.com/a076d05399.js" crossorigin="anonymous"></script>

  <style>
    body {
      font-family: 'Tajawal', sans-serif;
      text-align: center;
      padding-top: 50px;
      background-color: #f9f9f9;
      color: #333;
      transition: background-color 0.3s, color 0.3s;
    }

    @media (prefers-color-scheme: dark) {
      body {
        background-color: #121212;
        color: #f0f0f0;
      }
    }

    img {
      border-radius: 50%;
      width: 150px;
      margin-bottom: 20px;
      box-shadow: 0 6px 20px rgba(0, 0, 0, 0.2);
    }

    h1 {
      font-size: 2.2rem;
      margin-bottom: 10px;
    }

    p {
      font-size: 1.1rem;
      margin-bottom: 30px;
    }

    .btn {
      display: inline-block;
      padding: 12px 25px;
      margin: 10px;
      font-size: 1rem;
      border-radius: 12px;
      text-decoration: none;
      color: #fff;
      transition: transform 0.3s ease, box-shadow 0.3s ease;
    }

    .btn:hover {
      transform: translateY(-3px);
      box-shadow: 0 8px 20px rgba(0, 0, 0, 0.15);
    }

    .btn-cv {
      background: linear-gradient(45deg, #007bff, #00c6ff);
    }

    .btn-email {
      background: linear-gradient(45deg, #ff416c, #ff4b2b);
    }

    .btn-instagram {
      background: linear-gradient(45deg, #833ab4, #fd1d1d, #fcb045);
    }

    footer {
      margin-top: 40px;
      font-size: 0.9rem;
      color: #999;
    }

    footer a {
      color: inherit;
      text-decoration: none;
    }

    footer a:hover {
      text-decoration: underline;
    }
  </style>
</head>
<body>
  <main class="container">
    <img src="https://via.placeholder.com/150" alt="صورة شخصية لبدر" />
    <h1>مرحباً، أنا بدر</h1>
    <p>مطور مواقع شغوف بالتقنية والإبداع. تم تصميم هذا الموقع ليتوافق مع الهواتف الذكية 📱</p>

    <!-- زر السيرة الذاتية -->
    <a href="cv.pdf" class="btn btn-cv" target="_blank">
      <i class="fas fa-file-pdf"></i> عرض السيرة الذاتية
    </a>

    <!-- زر البريد -->
    <a href="mailto:kamadotanzhilang00@gmail.com" class="btn btn-email">
      <i class="fas fa-envelope"></i> راسلني عبر البريد
    </a>

    <!-- زر إنستاغرام -->
    <a href="https://instagram.com/yono555.empire" class="btn btn-instagram" target="_blank">
      <i class="fab fa-instagram"></i> تابعني على إنستاغرام
    </a>

    <p class="follow">💜 يسعدني دعمكم ومتابعتكم على إنستاغرام 🙏</p>
  </main>

  <footer>
    <p>&copy; 2025 بدر. جميع الحقوق محفوظة.</p>
  </footer>
</body>
</html>