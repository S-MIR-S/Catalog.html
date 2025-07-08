# Catalog.html
<!DOCTYPE html>
<html lang="ru">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Каталог — S.MIR.S</title>
  <style>
    body { margin: 0; font-family: Arial, sans-serif; background: #fff0f0; color: #111; }
    header, footer { background: #b30000; color: white; text-align: center; padding: 20px; }
    header img { max-height: 80px; margin-bottom: 10px; }
    .products { display: flex; flex-wrap: wrap; justify-content: center; gap: 20px; padding: 40px 20px; }
    .product {
      background: #fff;
      border: 2px solid #b30000;
      border-radius: 10px;
      width: 260px;
      padding: 20px;
      text-align: center;
    }
    .product img { width: 100%; height: 180px; object-fit: cover; border-radius: 6px; }
    .product h3 { color: #b30000; font-size: 16px; margin: 12px 0 8px; }
    .btn {
      display: inline-block;
      margin-top: 10px;
      background: #b30000;
      color: #fff;
      padding: 8px 12px;
      border-radius: 4px;
      text-decoration: none;
    }
    nav a { color: #fff; margin: 0 10px; text-decoration: underline; }
  </style>
</head>
<body>
  <header>
    <img src="https://i.postimg.cc/SKRGGp17/photo-2025-07-03-22-38-50.jpg" alt="Логотип"/>
    <h1>Каталог продукции</h1>
    <nav>
      <a href="index.html">О нас</a>
      <a href="contacts.html">Контакты и доставка</a>
    </nav>
  </header>

  <div class="products">
    <div class="product">
      <img src="https://i.postimg.cc/SKRGGp17/photo-2025-07-03-22-38-50.jpg" alt="Гель для наращивания"/>
      <h3>Гель для наращивания ногтей</h3>
      <p>Прочный, идеально держит форму. Подходит для профессионального моделирования.</p>
      <a href="contacts.html" class="btn">Заказать</a>
    </div>
    <div class="product">
      <img src="https://via.placeholder.com/250x180/ffcccc/000000?text=База"/>
      <h3>База под гель и гель-лаки</h3>
      <p>Надёжная основа с выравнивающим эффектом.</p>
      <a href="contacts.html" class="btn">Заказать</a>
    </div>
    <div class="product">
      <img src="https://via.placeholder.com/250x180/ffe0e0/000000?text=Топ"/>
      <h3>Топ для геля и гель-лака</h3>
      <p>Глянцевый или матовый финиш. Стойкое покрытие.</p>
      <a href="contacts.html" class="btn">Заказать</a>
    </div>
    <div class="product">
      <img src="https://via.placeholder.com/250x180/fff0f0/000000?text=Полигель"/>
      <h3>Полигель</h3>
      <p>Гибкость геля и прочность акрила в одном продукте.</p>
      <a href="contacts.html" class="btn">Заказать</a>
    </div>
  </div>

  <footer>
    <p>© 2025 S.MIR.S CO LIMITED COMPANY</p>
  </footer>
</body>
</html>
