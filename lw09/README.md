# Лабораторная работа №9 - Изучение принципов RESTful API

## Цель работы

Получить практические навыки в проектировании API в архитектурном стиле REST.
Познакомиться с реализацией API в ASP.NET Core.

## Ход выполнения работы

Всё очень просто: Вы должны пройти задания в учебнике по ссылке <https://docs.microsoft.com/ru-ru/aspnet/core/tutorials/first-web-api?view=aspnetcore-5.0&tabs=visual-studio> с некоторыми изменениями:

1. Название и содержимое класса модели должно отражать предметную область вашего сайта.
  Например, это может быть описание заказа, обращения по форме обратной связи, данных о доставке, клиентах и т.д.
  Однако имейте в виду, что `public long Id { get; set; }` лучше оставить.
  Также можете описать ограничения для строк (`[Required]` над названием свойства) и максимальную длины (там же `[MaxLength(255)]`).
  Доступ до атрибутов появится после установки _Entity Framework_ из _NuGet_.
2. Название контроллера также должно соответствовать названию класса модели.
3. "Вызов веб-API с помощью JavaScript" и далее делать не надо.
4. Работу с _Postman_ необходимо заскриншотить (вот это слово!) и приложить результаты к исходному коду приложения.

> Можно подумать, что преподаватель решил "обмануть систему" и вместо самостоятельного выдумывания задания подсунул статью от Microsoft.
> В какой-то степени так и есть, однако кто как не разработчики технологии могут научить обращаться с ней лучше, чем никто иной?

Задание желательно делать по следующей схеме:

1. Создать ветку в вашем репозитории с названием `aspnetcore-api`.
2. Создать директорию `aspnetcore-api`.
3. Выполнить задания учебника в этой директории.
4. Скопировать скриншоты также в директорию `aspnetcore-api` (если делали в документе _MS Word_, преобразуйте его, пожалуйста, в _PDF_).
5. Вылить ветку (`git pull`) в удалённый репозиторий и убедиться, что её видно на сайте гитхаба.
6. Зарегистрировать выполнение задания в [этой гугл-форме](https://forms.gle/JtvH11qHMv1MNmis5).
