# W-R-SPORT
<!DOCTYPE html>
<html lang="ar">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>RedWhite Sport</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>
  <header>
    <h1>أهلاً بكم في RedWhite Sport</h1>
  </header>

  <section id="products">
    <h2>منتجاتنا</h2>
    <div class="product">
      <img src="shoes.jpg" alt="حذاء رياضي">
      <p>حذاء رياضي 1200 جنيه</p>
    </div>
    <div class="product">
      <img src="tshirt.jpg" alt="تيشيرت">
      <p>تيشيرت رياضي 500 جنيه</p>
    </div>
  </section>

  <section id="delivery">
    <h2>خدمة التوصيل</h2>
    <p>لطلب المنتج، راسلنا على واتساب: <a href="https://wa.me/201207975389">01207975389</a></p>
  </section>

  <footer>
    <p>حقوق النشر © 2025 RedWhite Sport</p>
  </footer>
</body>
</html>
body {
  font-family: Arial, sans-serif;
  background-color: #fff;
  color: #000;
  margin: 0;
  padding: 0;
}

header {
  background-color: #ff0000;
  color: #fff;
  text-align: center;
  padding: 20px;
}

section {
  padding: 20px;
}

.product {
  border: 1px solid #ccc;
  display: inline-block;
  margin: 10px;
  padding: 10px;
}
