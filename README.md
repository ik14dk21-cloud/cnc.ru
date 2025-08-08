<!doctype html>
<html lang="ru">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>Школа ЧПУ Дмитрия Копылова — Программирование и Управление</title>
  <meta name="description" content="Обучение работе на станках с ЧПУ, написанию G-кода и CAM. Практика, реальные проекты, сертификация." />
  <script src="https://cdn.tailwindcss.com"></script>
</head>
<body class="bg-gray-50 text-gray-900 leading-relaxed">
  <header class="bg-white shadow-lg">
    <div class="max-w-7xl mx-auto px-6 py-6 flex items-center justify-between">
      <div class="flex items-center gap-4">
        <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/e/e3/CNC_endmill_and_sickle_logo.svg/120px-CNC_endmill_and_sickle_logo.svg.png" alt="Логотип: фреза и серп" class="w-12 h-12 rounded-md object-contain bg-gray-100 p-1">
        <div>
          <h1 class="text-2xl font-extrabold text-indigo-700">Школа ЧПУ Дмитрия Копылова</h1>
          <p class="text-sm text-gray-600">G-код, CAM, наладка станков, безопасность</p>
        </div>
      </div>
      <nav class="hidden md:flex gap-6 text-sm font-medium">
        <a href="#courses" class="hover:text-indigo-600">Курсы</a>
        <a href="#program" class="hover:text-indigo-600">Программа</a>
        <a href="#gallery" class="hover:text-indigo-600">Примеры работ</a>
        <a href="#advantages" class="hover:text-indigo-600">Преимущества</a>
        <a href="#instructors" class="hover:text-indigo-600">Преподаватели</a>
        <a href="#contact" class="bg-indigo-600 text-white px-4 py-2 rounded-md shadow hover:bg-indigo-700">Записаться</a>
      </nav>
    </div>
  </header>

  <main class="max-w-7xl mx-auto px-6 py-12">
    <!-- Hero -->
    <section class="grid md:grid-cols-2 gap-8 items-center">
      <div>
        <h2 class="text-4xl font-extrabold mb-4 text-indigo-800">Освойте работу на станках с ЧПУ — от новичка до профи</h2>
        <p class="text-lg text-gray-700 mb-6">Практика на реальном оборудовании, обучение написанию G-кода, CAM-программирование (Fusion 360, Mastercam), наладка и техника безопасности. Курсы подойдут как для начинающих, так и для специалистов, желающих поднять квалификацию.</p>
        <ul class="grid sm:grid-cols-2 gap-3 mb-6 text-gray-800">
          <li>✅ Практика на фрезерных и токарных ЧПУ</li>
          <li>✅ Ручное и автоматическое создание G-кода</li>
          <li>✅ CAM: стратегия обработки, оптимизация</li>
          <li>✅ Сертификация и помощь с трудоустройством</li>
        </ul>
        <a href="#contact" class="inline-block bg-indigo-600 text-white px-6 py-3 rounded-md shadow hover:bg-indigo-700">Записаться на пробное занятие</a>
      </div>
      <div class="rounded-lg overflow-hidden shadow-lg">
        <img src="https://images.unsplash.com/photo-1605170439002-8abca8f33f0f?auto=format&fit=crop&w=900&q=80" alt="Станок с ЧПУ" class="w-full h-full object-cover">
      </div>
    </section>

    <!-- Advantages -->
    <section id="advantages" class="mt-16 bg-white p-6 rounded-lg shadow">
      <h3 class="text-3xl font-bold mb-6 text-center">Почему выбирают нас</h3>
      <div class="grid md:grid-cols-3 gap-6 text-gray-700 text-sm">
        <div class="p-4 border rounded-lg">
          <h4 class="font-semibold mb-2">Современное оборудование</h4>
          <p>Наши ученики работают на станках Haas, FANUC и Siemens, а также учатся на профессиональных CAM-программах.</p>
        </div>
        <div class="p-4 border rounded-lg">
          <h4 class="font-semibold mb-2">Индивидуальный подход</h4>
          <p>Малые группы до 8 человек позволяют уделить внимание каждому ученику и проработать его проект.</p>
        </div>
        <div class="p-4 border rounded-lg">
          <h4 class="font-semibold mb-2">Помощь с карьерой</h4>
          <p>Мы предоставляем рекомендации и помогаем выпускникам устроиться в ведущие производственные компании.</p>
        </div>
      </div>
    </section>

    <!-- Gallery -->
    <section id="gallery" class="mt-16">
      <h3 class="text-3xl font-bold mb-6 text-center">Примеры работ наших учеников</h3>
      <div class="grid md:grid-cols-3 gap-6">
        <img src="https://images.unsplash.com/photo-1617196039897-944d8e7797a7?auto=format&fit=crop&w=600&q=80" alt="Деталь на фрезерном станке" class="rounded-lg shadow-md object-cover h-64 w-full">
        <img src="https://images.unsplash.com/photo-1581091870627-3b4b5b71e7b0?auto=format&fit=crop&w=600&q=80" alt="G-код на экране" class="rounded-lg shadow-md object-cover h-64 w-full">
        <img src="https://images.unsplash.com/photo-1617196039715-2c08a3c6d6e2?auto=format&fit=crop&w=600&q=80" alt="Фрезерная обработка" class="rounded-lg shadow-md object-cover h-64 w-full">
      </div>
    </section>

    <!-- Contact -->
    <section id="contact" class="mt-16 bg-indigo-50 p-6 rounded-lg">
      <h3 class="text-2xl font-bold mb-4">Свяжитесь с нами</h3>
      <form class="grid gap-4 md:grid-cols-2">
        <input type="text" placeholder="Ваше имя" class="p-2 rounded border">
        <input type="tel" placeholder="Телефон" class="p-2 rounded border">
        <input type="email" placeholder="E-mail" class="p-2 rounded border md:col-span-2">
        <textarea placeholder="Сообщение" class="p-2 rounded border md:col-span-2" rows="4"></textarea>
        <button class="bg-indigo-600 text-white py-2 rounded shadow hover:bg-indigo-700 md:col-span-2">Отправить</button>
      </form>
    </section>
  </main>

  <footer class="mt-12 text-center text-sm text-gray-600 bg-white py-6 shadow-inner">
    <p>© 2025 Школа ЧПУ Дмитрия Копылова. Все права защищены.</p>
  </footer>
</body>
</html>
