# Лабораторная работа №5. Введение в HTML
**ФИО**: Пономарёва Наталья Андреевна
**Группа**: ИСП-232
**Дата**: 05.03.2026

## Описание работы
В данной лабораторной работе создаётся проект для изучения основ HTML.
Настраиваем рабочую директорию, создаём базовые файлы, подключаем Git и GitHub, а также
подготавливаем HTML-файл для последующего изучения структуры веб-страницы.

Изучили основные теги: изображения, списки, заголовки, текст, ссылки и т.д. 

## Структура проекта
+ **index.html** — основной HTML-файл
+ **README.md** — описание лабораторной работы
+ **img/** — скриншоты
+ **about.html** — обо мне
+ **index2.html** — изучение блоков
+ **webpageCard.html** — визитка
---
## Теги в HTML

cтруктура парного тега:
**<тег>тело</тег>**
Пример:
```html
<h1>заголовок</h1>
```

## Базовые HTML-теги
### Примеры:
```html
<h2>Заголовок</h2>
<p>Абзац текста</p>
<strong>Жирный</strong>
<em>Курсив</em>
<hr>
<a href="https://example.com">Ссылка</a>
<img src="example.jpg" alt="Описание">
<ol>
        <li>1 пункт</li>
        <li>2 пункт</li>
        <li>3 пункт</li>
</ol>
<p id="intro">Это абзац с id</p>
<p class="highlight">Выделенный текст</p>
<p class="highlight big-text spaced">...</p>
<span title="Это подсказка!">Наведи на меня</span>
<p style="color: blue; font-size: 20px;">Синий текст</p>
<table border="1">
        <tr>
            <th>имя</th>
        </tr>
        <tr>
            <td>наталья</td>
        </tr>
</table>
<form>
    <label for="username">Имя:</label>
    <input id="username" type="text" placeholder="Введите имя">
    <br><br>
    <label for="city">Город:</label>
    <select id="city">
        <option>Волгоград</option>
        <option>Волжский</option>
    </select>
    <br><br>
    <label for="message">Сообщение:</label>
    <textarea id="message" rows="4" placeholder="Напишите текст..."></textarea>
    <br><br>
    <button type="submit">Отправить</button>
</form>
```
