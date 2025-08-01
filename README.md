<!DOCTYPE html>
<html lang="ar" dir="rtl">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Benkara Bees - بيع العسل الحر</title>
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
  <style>
    body {
      font-family: 'Segoe UI', sans-serif;
      background-color: #fffaf3;
      color: #4a3c1a;
      margin: 0;
      padding: 0;
      direction: rtl;
    }

    header {
      background-color: #f2c94c;
      padding: 20px;
      text-align: center;
    }

    header h1 {
      margin: 0;
      font-size: 32px;
    }

    nav {
      text-align: center;
      margin-top: 10px;
    }

    nav a {
      margin: 0 15px;
      color: #4a3c1a;
      text-decoration: none;
      font-weight: bold;
      transition: 0.3s;
    }

    nav a:hover {
      text-decoration: underline;
      color: #b48c24;
    }

    .section {
      padding: 30px;
      max-width: 800px;
      margin: auto;
    }

    .product {
      background-color: #fff3cd;
      padding: 20px;
      border-radius: 10px;
      margin-bottom: 20px;
      text-align: center;
    }

    .product img {
      width: 100%;
      max-width: 300px;
      border-radius: 10px;
      margin-top: 10px;
    }

    .btn {
      background-color: #4a3c1a;
      color: white;
      padding: 10px 20px;
      border: none;
      border-radius: 5px;
      margin-top: 15px;
      cursor: pointer;
      font-size: 16px;
      transition: background-color 0.3s;
    }

    .btn:hover {
      background-color: #6c552a;
    }

    form {
      background-color: #fff3cd;
      padding: 20px;
      border-radius: 10px;
      display: flex;
      flex-direction: column;
      gap: 10px;
    }

    input, textarea {
      padding: 10px;
      border: 1px solid #d4b15a;
      border-radius: 5px;
      font-family: inherit;
    }

    footer {
      background-color: #f2c94c;
      text-align: center;
      padding: 15px;
      margin-top: 30px;
    }

    @media (max-width: 600px) {
      nav a {
        display: block;
        margin: 10px 0;
      }

      header h1 {
        font-size: 24px;
      }
    }
  </style>
</head>
<body>
  <header>
    <h1>Benkara Bees</h1>
    <p>عسل حر طبيعي منذ 1962</p>
  </header>

  <nav>
    <a href="#about">من نحن</a>
    <a href="#products">المنتجات</a>
    <a href="#contact">اتصل بنا</a>
  </nav>

  <div class="section" id="about">
    <h2>من نحن</h2>
    <p>نحن عائلة بن قارة، نعمل في تربية النحل وإنتاج العسل الحر منذ عام 1962، نؤمن بجودة المنتج الطبيعي ونقدّمه مباشرة من خلايا النحل إلى زبائننا الأوفياء.</p>
  </div>

  <div class="section" id="products">
    <h2>منتجاتنا</h2>
    <div class="product">
      <h3>عسل حر طبيعي 1 كغ</h3>
      <p>السعر: 5000 دج</p>
      <p>عسل نقي، طبيعي 100٪، مصدره جبال الجزائر</p>
      <img src="https://i.imgur.com/DiHM5Zb.jpg" alt="عسل طبيعي">
      <button class="btn" onclick="window.location.href='#contact'">اطلب الآن</button>
    </div>
  </div>

  <div class="section" id="contact">
    <h2>اتصل بنا</h2>
    <p><i class="fa-solid fa-phone"></i> الهاتف: 0779917187</p>
    <p><i class="fa-solid fa-credit-card"></i> الدفع عبر CCP</p>
    <form>
      <input type="text" placeholder="الاسم الكامل" required>
      <input type="tel" placeholder="رقم الهاتف" required>
      <textarea rows="4" placeholder="رسالتك أو طلبك" required></textarea>
      <button class="btn" type="submit">إرسال</button>
    </form>
  </div>

  <footer>
    <p>&copy; 2025 Benkara Bees - كل الحقوق محفوظة</p>
  </footer>
</body>
</html>
