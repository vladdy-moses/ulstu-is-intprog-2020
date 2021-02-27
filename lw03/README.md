# Лабораторная работа №3 - Стилизация шаблона сайта (CSS)

## Цель работы

Освоение каскадных таблиц стилей в вебе (CSS3+).
Изучение основных селекторов и свойств CSS.

## Ход выполнения работы

1. Изучение практического видео-материала.
2. Добавление файла с каскадными таблицами стилей `styles.css` в папку с веб-страницами, созданными в л/р №2.
3. Подключение `styles.css` к html-файлам.
4. Определение необходимых правил стилизации для соответствия страниц макету, созданному в л/р №1.
5. Добавление селекторов и свойств CSS для стилизации.
6. Копирование исходных материалов в облачное хранилище.
7. Заполнение [google-формы](https://docs.google.com/forms/d/e/1FAIpQLSd1ml7uw3YMB9d5yOhvgkB1-GJoVeaYR4ZWo6Jg38024T69BQ/viewform?usp=sf_link).

## Срок сдачи работы

Для осеннего потока - до 02.11.2020 23:59 по Ульяновскому времени.

Для весеннего потока - до 14.03.2020 23:59 по Ульяновскому времени.

*Внимание!* Перед выполнением лабораторной работы убедитесь, что преподаватель проверил л/р №1.
Если это не так, пишите ему в телеграмме.

## Видео по теме лабораторной работы

[![](https://img.youtube.com/vi/_x0416c2IAM/0.jpg)](https://www.youtube.com/watch?v=_x0416c2IAM)

P.S. Для весеннего потока - можете смотреть видео в ускоренной перемотке, т.к. всё это есть в лекции №2.

## Примеры из видео

Подключение таблицы стилей в head-элементе страницы:

```html
<link rel="stylesheet" href="styles.css" />
```

Пример таблицы стилей:

```css
body {
    background-color: #eee;
    background-image: url(bg-1.png);
    color: #666;

    margin-top: 60px;
    margin-left: 1em;
    margin-right: 14pt;
    margin-bottom: 15px;
    /*same as "margin: 60px 14pt 15px 1em;"*/

    padding: 10px 50px;
    /*same as "padding: 10px 50px 10px 50px;"*/

    font-size: 14px;
    font-family: "Times New Roman", serif;
    font-weight: bold;
    
    text-transform: uppercase;
    text-align: center;
}

.card {
    border-width: 10px;
    border-color: red;
    border-radius: 10px;
}

.card.test-3 {
    position: absolute;
    top: 0;
    left: 55px;
    right: -50px;
    bottom: 20px;
    z-index: 9;
}

.card.test-4 {
    position: fixed;
    right: 20px;
    bottom: 20px;
}

.test {
    background-color: red;
}

td.test-2 {
    background-color: coral;
}

.test.test-2 {
    background-color: brown;
}

thead .test,
thead > tr.test > th {
    background-color: blue;
}

#main-container {
    background-color: aqua;
}

.test-5 {
    color: white;
}

.test-5 strong {
    color: red;
    display: block;
}

.test-6 {
    color: white;
    display: inline-block;
}
```

## Дополнительные темы для самостоятельного изучения

Если вам интересна интернет-вёрстка, можете изучить самостоятельно следующие темы:

* Адаптивная вёрстка.
* Верстка при помощи flexbox.
* Анимания в CSS3.
* Переменные в CSS3.
* Препроцессоры CSS: LESS, SASS/SCSS.
