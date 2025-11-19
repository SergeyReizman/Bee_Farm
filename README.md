🐝 Northern Apiary — Natural Honey from Central Russian Bees
Single-page website about the northern dark forest bee and natural honey with modern design and interactive elements.

https://images.unsplash.com/photo-1587049352846-4a5f9f0d65e1?ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%253D%253D&auto=format&fit=crop&w=1200&q=80

🎯 About the Project
Static website dedicated to the unique northern bee (Central Russian dark forest bee) and natural honey created in the wild conditions of the Pskov region. The page is designed with emphasis on visual cleanliness, simplicity, responsiveness, and fast loading.

🌐 Live Website: bee-farm.netlify.app
📂 Repository: github.com/SergeyReizman/bee-farm

✨ Project Features
🎨 Design and Interface
Modern minimalist design with warm honey color palette

Fully responsive layout - perfect display on all devices

Smooth animations and interactive hover effects

Clean typography (Inter, Arial) with optimal readability

Semantic HTML markup for better accessibility and SEO

🐝 Content and Functionality
Information about Central Russian dark forest bee - unique northern breed

Product catalog with prices and descriptions (flower, forest, comb honey)

Two contact forms - general and for orders

Interactive modal windows with additional information

Hero section with call to action

Customer testimonials section

Sticky navigation for user convenience

🚀 Quick Start
Option 1: Simple Launch

# Download the project archive and extract it
# Open index.html file in browser by double-clicking

Option 2: Git Cloning

git clone https://github.com/SergeyReizman/bee-farm.git
cd bee-farm
# Open index.html in browser

Option 3: Local Server (Optional)
For better performance, you can use a local server:

# Using Node.js (if installed)
npx http-server

# Or using Python
python -m http.server 8000

# Or using PHP
php -S localhost:8000

📁 Project Structure
text
northern-apiary/
│
├── index.html              # Main page (all styles and scripts inside)
├── README.md               # Documentation
└── assets/                 # Folder for additional resources
    ├── images/             # Project images
    └── icons/              # Icons and favicons
🛠️ Technology Stack
Technology	Purpose	Version
HTML5	Semantic markup, website structure	HTML5
CSS3	Styles, animations, responsive design	CSS3
JavaScript	Interactivity, modal windows, forms	ES6+
CSS Variables	Unified color and style system	CSS3
Google Fonts	Typography (Inter)	-
Flexbox/Grid	Modern layout	CSS3
🔧 Project Architecture
The project uses a monolithic approach with all styles and scripts in one file for easy deployment:

html
<!DOCTYPE html>
<html>
<head>
    <!-- Meta tags, title, styles -->
    <style>
        /* All CSS styles here */
    </style>
</head>
<body>
    <!-- Website content -->
    <script>
        // All JavaScript code here
    </script>
</body>
</html>
Main Components:
Header - Apiary name and title

Navigation - Sticky section navigation

Hero Section - Main banner with call to action

About Card - Information about the apiary and bees

Benefits Card - Advantages of our honey

Testimonials - Customer reviews

Products Grid - Product catalog with prices

Contact Form - Contact form

Modal Windows - Pop-up information and order windows

Footer - Footer with contacts and information

🖼️ Image Configuration
Main Hero Image
The project uses images from Unsplash. To replace with your own images:

html
<!-- Current image -->
<img src="https://images.unsplash.com/photo-1587049352846-4a5f9f0d65e1?ixlib=rb-4.0.3&auto=format&fit=crop&w=1200&q=80" alt="Apiary and northern dark bee" class="hero-image">

<!-- Example replacement with local image -->
<img src="assets/images/my-apiary-image.jpg" alt="Our apiary" class="hero-image">
Recommended parameters for images:

Size: 1200×600 px or larger

Format: JPG, PNG, WebP

Style: Apiary, bees, nature, honey

🌐 Deployment
The project is ready for deployment on any static hosting.

Supported hosting platforms:

Platform	Difficulty	Instructions
Netlify	🟢 Easy	Drag & Drop project folder
GitHub Pages	🟢 Easy	Repository Settings → Pages
Vercel	🟢 Easy	Import from Git
Firebase Hosting	🟡 Medium	Requires Firebase CLI
Render	🟢 Easy	Static Site
Deployment on Netlify:
Go to netlify.com

Drag and drop the project folder into "Drag and drop your site folder here" area

Done! The site is available at the provided URL

🔧 Customization
Changing Color Scheme
Edit CSS variables at the beginning of the file:

css
:root {
    --bg: #fefdf8;          /* Main background */
    --accent: #c19a2e;      /* Accent color (honey) */
    --accent-dark: #9c7a1f; /* Dark accent */
    --card: #ffffff;        /* Card background */
    --text: #2a2a2a;        /* Main text */
    --brown: #3b2b00;       /* Brown accent */
    --light-brown: #5a4a20; /* Light brown */
}
Changing Content
To update product information, edit the corresponding sections in HTML:

html
<!-- Example product update -->
<div class="product-card">
    <div class="product-image">
        <img src="new-image.jpg" alt="New product">
    </div>
    <div class="product-content">
        <h4 class="product-title">New Honey</h4>
        <p class="product-description">New product description</p>
        <div class="product-price">1500 ₽/kg</div>
        <button class="btn" onclick="showOrderModal('New Honey')">Order</button>
    </div>
</div>
Adding JavaScript Functionality
javascript
// Example of adding new function
function trackOrder(productName) {
    // Code for order tracking
    console.log(`Product ordered: ${productName}`);
}

// Adding event handlers
document.addEventListener('DOMContentLoaded', function() {
    // Code for initializing new functions
});
📈 Possible Improvements
🚀 Short-term Plans
Apiary photo gallery (Lightbox)

SEO optimization (meta tags, structured data)

Favicon and apple-touch-icon

JavaScript form validation

Scroll-triggered animations

Image loading optimization (lazy loading)

🔮 Future Development
Multi-language support

Beekeeping blog

Online store with shopping cart

Online ordering system with payment

Map with apiary location (Google Maps API)

Rating and review system

Social media integration

Email newsletter for regular customers

🐛 Debugging and Problem Solving
Frequently Asked Questions:
Q: Image doesn't display
A: Check:

Correct file path

File presence in project

Case sensitivity in file name

Availability of external resources (if using CDN)

Q: Modal window doesn't open
A: Make sure:

JavaScript is enabled in browser

No errors in developer console (F12)

showOrderModal() and showHoneyInfo() functions are defined

Q: Styles don't apply
A: Check:

Correct CSS syntax

No conflicting styles

Proper Google Fonts connection

Q: Form doesn't submit
A: In current version forms use simulated submission. For real functionality:

Set up backend for form processing

Add spam protection (reCAPTCHA)

Implement data validation

🤝 Contributing
We welcome contributions! Steps:

Fork the SergeyReizman/bee-farm repository

Create a feature branch (git checkout -b feature/amazing-feature)

Commit your changes (git commit -m 'Add amazing feature')

Push the branch (git push origin feature/amazing-feature)

Open a Pull Request

Code Style Guide:
Use semantic HTML5

Follow existing CSS structure with CSS variables

Comment complex JavaScript code sections

Test changes on different devices and browsers

📜 License
Distributed under the MIT License. See LICENSE file for details.

👨‍💻 Author
Sergey Reizman

GitHub: @SergeyReizman

Project: Northern Apiary

Repository: github.com/SergeyReizman/bee-farm

🌟 Acknowledgments
Fonts by Google Fonts

Images by Unsplash

Icons by Emoji

Hosting by Netlify

Inspiration from nature and bees 🐝

With love for bees and quality honey! 🍯

📞 Contact the author:
If you have questions or suggestions about the project, create an issue in the repository.

⭐ If you liked the project, don't forget to give it a star on GitHub!






🐝 Северная Пасека — Натуральный мёд от среднерусских пчёл
============================

Одностраничный сайт о северной тёмной лесной пчеле и натуральном мёде с современным дизайном и интерактивными элементами.

https://images.unsplash.com/photo-1587049352846-4a5f9f0d65e1?ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%253D%253D&auto=format&fit=crop&w=1200&q=80

🎯 О проекте
Статический веб-сайт, посвящённый уникальной северной пчеле (среднерусская тёмная лесная) и натуральному мёду, созданному в условиях дикой природы Псковской области. Страница оформлена с акцентом на визуальную чистоту, простоту, адаптивность и быструю загрузку.

🌐 Живой сайт: bee-farm.netlify.app
📂 Репозиторий: github.com/SergeyReizman/bee-farm

✨ Особенности проекта
🎨 Дизайн и интерфейс
Современный минималистичный дизайн с тёплой медовой цветовой палитрой

Полностью адаптивная верстка — идеальное отображение на всех устройствах

Плавные анимации и интерактивные hover-эффекты

Чистая типографика (Inter, Arial) с оптимальной читаемостью

Семантическая HTML-разметка для лучшей доступности и SEO

🐝 Контент и функциональность
Информация о среднерусской тёмной лесной пчеле — уникальной северной породе

Каталог продукции с ценами и описаниями (цветочный, лесной, сотовый мёд)

Две контактные формы — общая и для заказов

Интерактивные модальные окна с дополнительной информацией

Hero-секция с призывом к действию

Секция с отзывами покупателей

Липкая навигация для удобства пользователей

🚀 Быстрый старт
Вариант 1: Простой запуск
bash
# Скачайте архив проекта и распакуйте
# Откройте файл index.html в браузере двойным кликом
Вариант 2: Git клонирование
bash
git clone https://github.com/SergeyReizman/bee-farm.git
cd bee-farm
# Откройте index.html в браузере
Вариант 3: Локальный сервер (опционально)
Для лучшей производительности можно использовать локальный сервер:

bash
# С помощью Node.js (если установлен)
npx http-server

# Или с помощью Python
python -m http.server 8000

# Или с помощью PHP
php -S localhost:8000
📁 Структура проекта
text
northern-apiary/
│
├── index.html              # Главная страница (все стили и скрипты внутри)
├── README.md               # Документация
└── assets/                 # Папка для дополнительных ресурсов
    ├── images/             # Изображения проекта
    └── icons/              # Иконки и фавиконы
🛠️ Технологический стек
Технология	Назначение	Версия
HTML5	Семантическая разметка, структура сайта	HTML5
CSS3	Стили, анимации, адаптивный дизайн	CSS3
JavaScript	Интерактивность, модальные окна, формы	ES6+
CSS Variables	Единая система цветов и стилей	CSS3
Google Fonts	Типографика (Inter)	-
Flexbox/Grid	Современная верстка	CSS3
🔧 Архитектура проекта
Проект использует монолитный подход со всеми стилями и скриптами в одном файле для простоты развёртывания:

html
<!DOCTYPE html>
<html>
<head>
    <!-- Мета-теги, заголовок, стили -->
    <style>
        /* Все CSS стили здесь */
    </style>
</head>
<body>
    <!-- Контент сайта -->
    <script>
        // Весь JavaScript код здесь
    </script>
</body>
</html>
Основные компоненты:
Header - Заголовок с названием пасеки

Navigation - Липкая навигация по разделам

Hero Section - Главный баннер с призывом к действию

About Card - Информация о пасеке и пчёлах

Benefits Card - Преимущества нашего мёда

Testimonials - Отзывы покупателей

Products Grid - Каталог продукции с ценами

Contact Form - Форма обратной связи

Modal Windows - Всплывающие окна информации и заказов

Footer - Подвал с контактами и информацией

🖼️ Настройка изображений
Основное hero-изображение
Проект использует изображения с Unsplash. Для замены на свои изображения:

html
<!-- Текущее изображение -->
<img src="https://images.unsplash.com/photo-1587049352846-4a5f9f0d65e1?ixlib=rb-4.0.3&auto=format&fit=crop&w=1200&q=80" alt="Пасека и северная тёмная пчела" class="hero-image">

<!-- Пример замены на локальное изображение -->
<img src="assets/images/my-paseka-image.jpg" alt="Наша пасека" class="hero-image">
Рекомендуемые параметры для изображений:

Размер: 1200×600 px или больше

Формат: JPG, PNG, WebP

Стиль: Пасека, пчёлы, природа, мёд

🌐 Деплой (развёртывание)
Проект готов к развёртыванию на любой статический хостинг.

Поддерживаемые платформы для хостинга:

Платформа	Сложность	Инструкция
Netlify	🟢 Легко	Drag & Drop папки проекта
GitHub Pages	🟢 Легко	Настройки репозитория → Pages
Vercel	🟢 Легко	Import from Git
Firebase Hosting	🟡 Средне	Требует Firebase CLI
Render	🟢 Легко	Static Site
Деплой на Netlify:
Перейдите на netlify.com

Перетащите папку проекта в область "Drag and drop your site folder here"

Готово! Сайт доступен по предоставленному URL

🔧 Кастомизация
Изменение цветовой схемы
Отредактируйте CSS-переменные в начале файла:

css
:root {
    --bg: #fefdf8;          /* Основной фон */
    --accent: #c19a2e;      /* Акцентный цвет (медовый) */
    --accent-dark: #9c7a1f; /* Тёмный акцент */
    --card: #ffffff;        /* Фон карточек */
    --text: #2a2a2a;        /* Основной текст */
    --brown: #3b2b00;       /* Коричневый акцент */
    --light-brown: #5a4a20; /* Светло-коричневый */
}
Изменение контента
Для обновления информации о продукции отредактируйте соответствующие разделы в HTML:

html
<!-- Пример обновления продукта -->
<div class="product-card">
    <div class="product-image">
        <img src="new-image.jpg" alt="Новый продукт">
    </div>
    <div class="product-content">
        <h4 class="product-title">Новый мёд</h4>
        <p class="product-description">Описание нового продукта</p>
        <div class="product-price">1500 ₽/кг</div>
        <button class="btn" onclick="showOrderModal('Новый мёд')">Заказать</button>
    </div>
</div>
Добавление JavaScript функциональности
javascript
// Пример добавления новой функции
function trackOrder(productName) {
    // Код для отслеживания заказов
    console.log(`Заказан продукт: ${productName}`);
}

// Добавление обработчиков событий
document.addEventListener('DOMContentLoaded', function() {
    // Код для инициализации новых функций
});
📈 Возможные улучшения
🚀 Ближайшие планы
Галерея фотографий пасеки (Lightbox)

SEO оптимизация (meta-теги, структурированные данные)

Favicon и apple-touch-icon

Валидация формы на JavaScript

Анимации при скролле (Scroll-triggered animations)

Оптимизация загрузки изображений (lazy loading)

🔮 Дальнейшее развитие
Многоязычная поддержка

Блог о пчеловодстве

Интернет-магазин с корзиной

Система онлайн-заказов с оплатой

Карта с расположением пасеки (Google Maps API)

Система рейтингов и отзывов

Интеграция с социальными сетями

Email-рассылка для постоянных клиентов

🐛 Отладка и решение проблем
Частые вопросы:
Q: Изображение не отображается
A: Проверьте:

Правильность пути к файлу

Наличие файла в проекте

Регистр в названии файла

Доступность внешних ресурсов (если используете CDN)

Q: Модальное окно не открывается
A: Убедитесь, что:

JavaScript включен в браузере

Нет ошибок в консоли разработчика (F12)

Функции showOrderModal() и showHoneyInfo() определены

Q: Стили не применяются
A: Проверьте:

Корректность CSS синтаксиса

Отсутствие конфликтующих стилей

Правильность подключения Google Fonts

Q: Форма не отправляется
A: В текущей версии формы используют имитацию отправки. Для реальной работы:

Настройте бэкенд для обработки форм

Добавьте защиту от спама (reCAPTCHA)

Реализуйте валидацию данных

🤝 Участие в разработке
Мы приветствуем contributions! Порядок действий:

Форкните репозиторий SergeyReizman/bee-farm

Создайте ветку для фичи (git checkout -b feature/amazing-feature)

Закоммитьте изменения (git commit -m 'Add amazing feature')

Запушьте ветку (git push origin feature/amazing-feature)

Откройте Pull Request

Руководство по стилю кода:
Используйте семантический HTML5

Следуйте существующей структуре CSS с CSS-переменными

Комментируйте сложные участки JavaScript кода

Тестируйте изменения на разных устройствах и браузерах

📜 Лицензия
Распространяется под лицензией MIT. Смотрите файл LICENSE для подробностей.

👨‍💻 Автор
Sergey Reizman

GitHub: @SergeyReizman

Проект: Северная Пасека

Репозиторий: github.com/SergeyReizman/bee-farm

🌟 Благодарности
Шрифты от Google Fonts

Изображения от Unsplash

Иконки от Emoji

Хостинг от Netlify

Вдохновение природой и пчёлами 🐝

С любовью к пчёлам и качественному мёду! 🍯

📞 Связь с автором:
Если у вас есть вопросы или предложения по проекту, создайте issue в репозитории.

⭐ Если проект вам понравился, не забудьте поставить звезду на GitHub!