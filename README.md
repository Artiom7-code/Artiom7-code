- 👋 Hi, I’m @Artiom7-code<!DOCTYPE html>
<html lang="ru">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>ArtiΩm Electric Grup</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      margin: 0;
      padding: 0;
      background-color: #1d1d1d;
      color: #fff;
    }
    header {
      background-color: #FFCD00;
      padding: 20px;
      text-align: center<!DOCTYPE html>
<html lang="ru">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>ArtiΩm Electric Grup</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      margin: 0;
      padding: 0;
      background-color: #1d1d1d;
      color: #fff;
    }
    header {
      background-color: #FFCD00;
      padding: 20px;
      text-align: center;
    }
    header h1 {
      font-size: 36px;
      color: #000;
    }
    nav ul {
      list-style-type: none;
      padding: 0;
    }
    nav ul li {
      display: inline;
      margin: 0 15px;
    }
    nav ul li a {
      color: #000;
      text-decoration: none;
      font-weight: bold;
    }
    section {
      padding: 50px 20px;
    }
    section h2 {
      font-size: 32px;
      color: #FFCD00;
      text-align: center;
    }
    .service {
      padding: 15px;
      background-color: #333;
      margin-bottom: 20px;
      border-radius: 5px;
    }
    .service h3 {
      color: #FFCD00;
    }
    .service img {
      width: 100%;
      height: auto;
      border-radius: 5px;
    }
    .contact-info {
      display: flex;
      justify-content: center;
      gap: 30px;
      margin-top: 20px;
    }
    .contact-info div {
      text-align: center;
    }
    footer {
      background-color: #000;
      color: #fff;
      padding: 10px 0;
      text-align: center;
    }
    footer p {
      margin: 0;
    }
    form input, form textarea, form button {
      width: 100%;
      padding: 10px;
      margin: 10px 0;
      border: none;
      border-radius: 5px;
    }
    form button {
      background-color: #FFCD00;
      color: #000;
      cursor: pointer;
    }
    form button:hover {
      background-color: #E0A800;
    }
    .lightning {
      font-size: 2em;
      color: #FFCD00;
      display: inline-block;
      transform: rotate(45deg);
      margin-left: 10px;
    }
    .reviews {
      background-color: #333;
      padding: 20px;
      margin-top: 30px;
      border-radius: 5px;
    }
    .review {
      margin-bottom: 20px;
    }
    .review h3 {
      color: #FFCD00;
    }
    .review p {
      font-style: italic;
    }
  </style>
</head>
<body>

  <!-- Header -->
  <header>
    <div class="logo">
      <h1>ArtiΩm Electric Grup <span class="lightning">⚡</span></h1>
    </div>
    <nav>
      <ul>
        <li><a href="#services">Услуги</a></li>
        <li><a href="#about">О нас</a></li>
        <li><a href="#contact">Контакты</a></li>
        <li><a href="#reviews">Отзывы</a></li>
      </ul>
    </nav>
  </header>

  <!-- Main Section -->
  <section id="home">
    <h2>Добро пожаловать в ArtiΩm Electric Grup</h2>
    <p>Мы предлагаем профессиональные услуги в области электрики. Работы по установке, проектированию и обслуживанию электрических систем.</p>
  </section>

  <!-- Services Section -->
  <section id="services">
    <h2>Наши Услуги</h2>
    <div class="service">
      <h3>Монтаж электрооборудования</h3>
      <img src="https://via.placeholder.com/800x400.png?text=Электрическое+оборудование" alt="Монтаж электрооборудования">
      <p>Качественная установка и настройка электрических приборов для вашего дома или бизнеса.</p>
    </div>
    <div class="service">
      <h3>Проектирование электрических схем</h3>
      <img src="https://via.placeholder.com/800x400.png?text=Проектирование+схем" alt="Проектирование электрических схем">
      <p>Разработка и реализация схем для различных типов объектов.</p>
    </div>
    <div class="service">
      <h3>Диагностика электрических систем</h3>
      <img src="https://via.placeholder.com/800x400.png?text=Диагностика+систем" alt="Диагностика электрических систем">
      <p>Проверка и диагностика существующих систем для обеспечения их безопасности и эффективности.</p>
    </div>
  </section>

  <!-- Contact Section -->
  <section id="contact">
    <h2>Контакты</h2>
    <div class="contact-info">
      <div>
        <p><strong>Телефон:</strong> +33 7 53 17 55 90</p>
      </div>
      <div>
        <p><strong>Электронная почта:</strong> artiomelectricgrup@gmail.com</p>
      </div>
    </div>
    <form action="https://formspree.io/f/{YOUR_FORM_ID}" method="POST">
      <input type="text" name="name" placeholder="Ваше имя" required />
      <input type="email" name="email" placeholder="Ваш email" required />
      <textarea name="message" placeholder="Ваше сообщение" rows="5" required></textarea>
      <button type="submit">Отправить</button>
    </form>
  </section>

  <!-- Reviews Section -->
  <section id="reviews">
    <h2>Отзывы клиентов</h2>
    <div class="reviews">
      <div class="review">
        <h3>Иван П.</h3>
        <p>"Отличная работа! Все сделано быстро и качественно. Буду обращаться снова!"</p>
      </div>
      <div class="review">
        <h3>Марина Л.</h3>
        <p>"Очень профессиональные и вежливые специалисты. Установили все электрические системы в доме без проблем!"</p>
      </div>
    </div>
  </section>

  <!-- Footer -->
  <footer>
    <p>&copy; 2025 ArtiΩm Electric Grup</p>
  </footer>

</body>
</html>

    }
    header h1 {
      font-size: 36px;
      color: #000;
    }
    nav ul {
      list-style-type: none;
      padding: 0;
    }
    nav ul li {
      display: inline;
      margin: 0 15px;
    }
    nav ul li a {
      color: #000;
      text-decoration: none;
      font-weight: bold;
    }
    section {
      padding: 50px 20px;
    }
    section h2 {
      font-size: 32px;
      color: #FFCD00;
      text-align: center;
    }
    .service {
      padding: 15px;
      background-color: #333;
      margin-bottom: 20px;
      border-radius: 5px;
    }
    .service h3 {
      color: #FFCD00;
    }
    footer {
      background-color: #000;
      color: #fff;
      padding: 10px 0;
      text-align: center;
    }
    footer p {
      margin: 0;
    }
    form input, form textarea, form button {
      width: 100%;
      padding: 10px;
      margin: 10px 0;
      border: none;
      border-radius: 5px;
    }
    form button {
      background-color: #FFCD00;
      color: #000;
      cursor: pointer;
    }
    form button:hover {
      background-color: #E0A800;
    }
  </style>
</head>
<body>

  <!-- Header -->
  <header>
    <div class="logo">
      <h1>ArtiΩm Electric Grup</h1>
    </div>
    <nav>
      <ul>
        <li><a href="#services">Услуги</a></li>
        <li><a href="#about">О нас</a></li>
        <li><a href="#contact">Контакты</a></li>
      </ul>
    </nav>
  </header>

  <!-- Main Section -->
  <section id="home">
    <h2>Добро пожаловать в ArtiΩm Electric Grup</h2>
    <p>Мы предлагаем профессиональные услуги в области электрики. Работы по установке, проектированию и обслуживанию электрических систем.</p>
  </section>

  <!-- Services Section -->
  <section id="services">
    <h2>Наши Услуги</h2>
    <div class="service">
      <h3>Монтаж электрооборудования</h3>
      <p>Качественная установка и настройка электрических приборов для вашего дома или бизнеса.</p>
    </div>
    <div class="service">
      <h3>Проектирование электрических схем</h3>
      <p>Разработка и реализация схем для различных типов объектов.</p>
    </div>
    <div class="service">
      <h3>Диагностика электрических систем</h3>
      <p>Проверка и диагностика существующих систем для обеспечения их безопасности и эффективности.</p>
    </div>
  </section>

  <!-- About Section -->
  <section id="about">
    <h2>О нас</h2>
    <p>Мы с гордостью предлагаем профессиональные электрические услуги с многолетним опытом работы и качественным обслуживанием.</p>
  </section>

  <!-- Contact Section -->
  <section id="contact">
    <h2>Контакты</h2>
    <form action="https://formspree.io/f/{YOUR_FORM_ID}" method="POST">
      <input type="text" name="name" placeholder="Ваше имя" required />
      <input type="email" name="email" placeholder="Ваш email" required />
      <textarea name="message" placeholder="Ваше сообщение" rows="5" required></textarea>
      <button type="submit">Отправить</button>
    </form>
  </section>

  <footer>
    <p>&copy; 2025 ArtiΩm Electric Grup</p>
  </footer>

</body>
</html>
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
https://via.plac
