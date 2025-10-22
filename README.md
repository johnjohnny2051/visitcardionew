<!DOCTYPE html>
<html lang="ru">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <meta name="description" content="Профессиональный сайт-визитка Ивана Иванова — веб-разработчик и дизайнер. Здесь представлена информация о навыках, опыте и контактах." />
  <meta name="keywords" content="веб-разработчик, дизайнер, сайт визитка, портфолио, Иван Иванов" />
  <meta name="author" content="Иван Иванов" />
  <title>Иван Иванов — веб-разработчик и дизайнер</title>
  <style>
  h1{
    color: red
  }
</head>
<body itemscope itemtype="https://schema.org/Person">
  <header>
    <h1 itemprop="name">Иван Иванов</h1>
    <p><strong>Профессия:</strong> <span itemprop="jobTitle">Веб-разработчик и дизайнер</span></p>
    <nav aria-label="Основное меню">
      <ul>
        <li><a href="#about">Обо мне</a></li>
        <li><a href="#skills">Навыки</a></li>
        <li><a href="#experience">Опыт работы</a></li>
        <li><a href="#contacts">Контакты</a></li>
      </ul>
    </nav>
  </header>

  <main>
    <section id="about" itemprop="description">
      <h2>Обо мне</h2>
      <p>Меня зовут Иван Иванов. Я профессиональный веб-разработчик и дизайнер с более чем 7-летним опытом работы в создании современных, адаптивных и удобных для пользователя сайтов и приложений. Моя цель — создавать качественные цифровые решения, которые помогают бизнесам расти и развиваться.</p>
      <p>Я владею широким спектром технологий, включая HTML5, CSS3, JavaScript, React, а также различными инструментами дизайна и прототипирования. Мне нравится структурировать информацию и разрабатывать интерфейсы, которые понятны и привлекательны для конечного пользователя.</p>
      <p>За годы работы я реализовал более 50 проектов для клиентов из различных сфер: от стартапов до крупных корпораций. Каждый проект для меня — это возможность применить свои знания, а также найти творческий подход для достижения оптимального результата.</p>
    </section>

    <section id="skills">
      <h2>Навыки и технологии</h2>
      <ul>
        <li>Разработка на HTML5, CSS3, JavaScript (ES6+)</li>
        <li>Фреймворки и библиотеки: React, Vue.js</li>
        <li>Программирование на PHP, Node.js</li>
        <li>Базы данных: MySQL, MongoDB</li>
        <li>Адаптивный и кроссбраузерный дизайн</li>
        <li>Использование препроцессоров: SASS, LESS</li>
        <li>Опыт работы с системами контроля версий Git</li>
        <li>Основы UX/UI дизайна и прототипирования</li>
      </ul>
      <p>Кроме технических навыков, я умею работать с клиентами и четко понимать задачи проекта, что позволяет создавать успешные и эффек­тивные продукты. Коммуникация и постоянное обучение — ключевые составляющие моего профессионального роста.</p>
    </section>

    <section id="experience" itemprop="hasOccupation" itemscope itemtype="https://schema.org/Occupation">
      <h2>Опыт работы</h2>
      <article itemprop="jobTitle">
        <h3>Веб-разработчик в компании «Tech Solutions»</h3>
        <p><time datetime="2020-01">Январь 2020</time> — настоящее время</p>
        <p>Разработка и поддержка корпоративного сайта, внедрение новых функций, оптимизация производительности и обеспечение безопасности веб-приложения. Работа в команде Agile, взаимодействие с дизайнерами и маркетологами для создания успешных цифровых продуктов.</p>
      </article>
      <article>
        <h3>Фронтенд-разработчик в студии «WebArt»</h3>
        <p><time datetime="2017-06">Июнь 2017</time> — <time datetime="2019-12">Декабрь 2019</time></p>
        <p>Участие в создании проектов электронной коммерции: разработка интерфейсов, оптимизация юзабилити и улучшение визуальной составляющей сайтов. Создание отзывчивых и доступных пользовательских интерфейсов с использованием современных технологий и стандартов.</p>
      </article>
    </section>

    <section id="contacts" itemprop="contactPoint" itemscope itemtype="https://schema.org/ContactPoint">
      <h2>Контакты</h2>
      <p><strong>Электронная почта:</strong> <a href="mailto:ivan.ivanov@example.com" itemprop="email">ivan.ivanov@example.com</a></p>
      <p><strong>Телефон:</strong> <a href="tel:+79991234567" itemprop="telephone">+7 (999) 123-45-67</a></p>
      <p><strong>Портфолио:</strong> <a href="https://portfolio.ivanov.ru" itemprop="url" target="_blank" rel="noopener noreferrer">portfolio.ivanov.ru</a></p>
      <p><meta itemprop="availableLanguage" content="Русский, Английский" /></p>
    </section>
  </main>

  <footer>
    <p>© 2025 Иван Иванов. Все права защищены.</p>
  </footer>
</body>
</html>
