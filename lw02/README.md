# Лабораторная работа №2 - Создание шаблона сайта (HTML)

## Цель работы

Освоение основ интернет-вёртски.
Ознакомление и использовании библиотеки построения интерфейсов boostrap 4.

## Ход выполнения работы

1. Изучение основопологающих принципов интернет-вёрстки: HTML-документ, теги, поток документа, блочные и строчные элементы, таблицы.
2. Изучение основных элементов веб-страницы: заголовок и тело документа, абзац, заголовок текста, таблица, ссылка, изображение.
3. Изучение grid system из bootstrap 4. Разделение своего макета на слои.
4. Изучение библиотеки компонентов из bootstrap 4. Наполнение слоёв контентом.

## Срок сдачи работы

До 11.10.2020 23:59 по Ульяновскому времени.

## Видео по теме лабораторной работы

[![](https://img.youtube.com/vi/7_DpTyVrUdM/0.jpg)](https://www.youtube.com/watch?v=7_DpTyVrUdM)

## Изучение принципов интернет вёрстки

На этом этапе выполнения рабораторной работы необходимо усвоить, что такое интернет-вёрстка (похожа ли она на вёрстку газет, например), в чём отличие и схожесть HTML и обычного текстового документа, из чего состоит веб-страница внутри и по каким принципам обычно свёрстаны веб-сайты.

См. следующий материал:

* Введение в HTML - http://htmlbook.ru/samhtml/vvedenie-v-html
* Про теги - http://htmlbook.ru/samhtml/tegi
* Про историю проблем с вёрсткой - http://htmlbook.ru/samlayout
* Про табличную вёрстку (сейчас считается устаревшим) - http://htmlbook.ru/samlayout/verstka-s-pomoshchyu-tablits/osobennosti-tablits
* Про блочную вёрстку - http://htmlbook.ru/samlayout/blochnaya-verstka (и все подстраницы этого раздела)

Также в источниках упоминается CSS (или каскадные таблицы стилей).
Их мы будем проходить несколько позже, однако сейчас вы уже можете догадаться, что эти таблицы необходимы для стилизации контента на веб-странице.

## Изучение основных элементов веб-страницы

Когда вы разберётесь в том, что такое вёртка веб-страниц, необходимо ознакомиться с тем, из каких элементов может состоять документ HTML (или наша веб-страница).

Элементов много, но всё сводится к нескольким блочным (то есть блокам - заголовок, абзац, таблица, контейнер без явного смысла и др.) и строчным (изображение, всевозможные выделения текста, блок текста без явного смысла и др.) элементам.

Для "пробы пера" можете использовать JSFiddle, песочницу для вёрстки на bootstrap и не только - <https://jsfiddle.net/boilerplate/bootstrap>.

См. следующий материал:

* HTML5 и CSS3 на примерах - https://webref.ru/layout/html5-css3
* Справочник по HTML - http://htmlbook.ru/html

Также будет полезно прочитать про типографику и построение таблиц в bootstrap 4:

* https://bootstrap-4.ru/docs/4.5/content/typography/
* https://bootstrap-4.ru/docs/4.5/content/tables/

## Grid system в bootstrap 4

На этом этапе выполнения лабораторной работы вам уже необходимо рассмотреть тот шаблон, что вы сделали в [предыдущей работе](../lw01/README.md).

Перед этим необходимо разобраться с контейнерами и сеткой в bootstrap 4, ссылки на материал о которых ниже.

Затем требуется оценить, сколько строк и какие колонки в них будут будущем веб-сайте.

После этого необходимо создать веб-документ (текстовый файл `index.html`), подключить туда bootstrap и начать творить.
Информация об этом есть в видео.
Об этом же рассказывалось на практике в субботу 26.09.2020 г.

На этом этапе также можно использовать JSFiddle.

* Про контейнеры - https://getbootstrap.com/docs/4.5/layout/overview/ (на русском: https://bootstrap-4.ru/docs/4.5/layout/overview/)
* Про саму систему с сеткой - https://getbootstrap.com/docs/4.5/layout/grid/ (на русском: https://bootstrap-4.ru/docs/4.5/layout/grid/)

## Наполнение своего сайта контентом

На этом этапе необходимо тот веб-документ, который Вы создали на предыдущем этапе, наполнить контентом.

В итоге должно получиться что-то похожее на ваш макет но только без ваших цветов, шрифтов, изображений и прочего.
Зато должно быть явно видно, где у вас меню, где боковая панель (если она вообще есть на макете), где подвал и т.д.

Ещё раз напомню, что конечная стилизация, максимальная приближенная, под макет требует знаний каскадных таблиц стилей CSS и будет выполнена в следующих лабораторных работах.

У вас в макете должно быть несколько страниц с различным контентом: с таблицами, формами и т.д.
Для каждой такой страницы в figma (или аналогичном редакторе) Вы создавали свой фрейм.
Сейчас же для каждого фрейма необходимо будет сделать свою веб-страницу.
Физически это будут разные файлы с расширением html.
Главная страница будет называться index (так исторически положено), остальные лучше называть английскими словами, например, orders.html, list.html, very-interesting-page.html.

Если Вы используете изображения, можете их скопировать или рядом с веб-старницей, или положить в подпапку, или использовать URL.

Справочник компонентов библиотеки bootstrap - https://getbootstrap.com/docs/4.5/components/alerts/ и далее (на русском: https://bootstrap-4.ru/docs/4.5/components/alerts/ и далее). 

## Пример того, что делали на практике

В субботу 26 сентября состоялось практическое занятие, где, как и в видео, объяснялись основы интернет-вёрстки.

Пример того, что мы сотворили с одной из подгрупп можете видеть [тут](./example.html).

## Отправка задания на проверку 

Необходимо [заполнить гугл-форму](https://docs.google.com/forms/d/e/1FAIpQLSfPVCbZejZctdPypaK0hGbV3wF6QiIx9U4ZCJNtKFqBX6LBYA/viewform?usp=sf_link).

Все подробности описаны в ней.

> Изначально предполагалось использовать JSFiddle.
> Но там нельзя размещать несколько страниц и копировать изображения.
> Наверняка есть другие сервисы, где это сделать можно, однако в этот раз будем использовать облачные хранилища.