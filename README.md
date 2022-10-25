# Разработка Интернет Приложений (РИП) 2022

## [Видеозаписи лекций в youtube](https://youtube.com/playlist?list=PLLELLTvDgUQ9cpB1XzSuZ0mNSBkbjVNJ_)

## Лекции
### Бекенд
[Лекция 1. История Web, трехуровневая модель приложений, MVC](https://github.com/iu5git/web-2022/blob/main/lectures/web_intro.pdf) 

[Лекция 2. Методология Agile, состав команды. Диаграммы UML](https://github.com/iu5git/web-2022/blob/main/lectures/Lecture_2_Agile_UML.pdf)

[Лекция 3. Основы Web, шаблонизация, Django](https://github.com/iu5git/web-2022/blob/main/lectures/Lecture_3_Web_Django.pdf)

[Лекция 4. Базы данных, ER, PostgreSQL. ORM. Админка Django. Курсоры](https://github.com/iu5git/web-2022/blob/main/lectures/Lecture_4_Databases_Django_ORM.pdf)

[Лекция 5. Веб-сервис. Swagger. Микросервисы](https://github.com/iu5git/web-2022/blob/main/lectures/Lecture_5_Web_Service.pdf)

[Лекция 6. Работа в git. Примеры специализированных сервисов - S3, уведомления, очереди](https://github.com/iu5git/web-2022/blob/main/lectures/Lecture_6_Special_Services.pdf)

### Фронтенд
[Лекция 7. Введение в фронтенд и React](https://github.com/iu5git/web-2022/blob/main/lectures/Lecture_7_React_Introduction.pdf)

Лекция 8. React, навигация, TypeScript. 

Лекция 9. Ajax, запросы на React

Лекция 10. Redux. WebSocket

Лекция 11. Авторизация, куки, токены, хранилище сессий. 

Лекция 12. SSO. Ограничение прав на части приложения. 

### Мобильные приложения

Лекция 13. Общая лекция про мобильные приложения. Верстка

Лекция 14. Конкретные кейсы с примерами кода. Сетевое взаимодействие. 

Лекция 15. Деплой, DevOps, RE

## Лабораторные работы
У каждого своя предметная область на весь курс: бронирование отелей, билетов в театр/кинотеатр, онлайн-магазин

Основной вариант лаб по беку - это Django. Но есть ещё варианты на `Go`, `Java`, `C#` и `Node.js`

При защите необходимо продемонстрировать работу приложения, UML диаграмму, репозиторий github с кодом и ответить на вопросы.

#### Лабораторная работа №1
Базовая шаблонизация в Django для словаря. Создание базового интерфейса для просмотра списка (отели, товары, рейсы и тд) с ссылками и частью полей (цена, город) и при переходе по ссылке другая страница с более подробной информацией о товаре (описание, картинка и тд). В приложении должны быть использованы стили, для каждого элемента списка подгружается свое изображение. 

На выбор `Django`, `Go`, `Spring`, `Node.js`

Контрольные вопросы: MVC, Django, шаблонизация, HTTP, Web, HTML

* [Методические указания](https://github.com/iu5git/web-2022/blob/main/tutorials/lab1/lab1_tutorial.md)

#### Лабораторная работа №2
Создание базы данных PostgreSQL/MySQL (SQLite использовать нельзя), подключение к шаблонизатору. Создание админки.
Добавить возможность на основной странице при нажатии на кнопку с помощью курсора вставлять новые записи в таблицу услуг. 

Таблицы: таблица услуг - словарь, таблица фактов - бронирования (с датами и статусом, три даты и менеджер), таблица пользователей

Статусы: введен, в работе, завершён, удалён

ER диаграмма: таблицы, связи, столбцы, типы столбцов и их длина, первичные, вторичные ключи

Контрольные вопросы: ORM, SQL, модель и миграции

* [Методические указания](https://github.com/iu5git/web-2022/blob/main/tutorials/lab2/lab2_tutorial.md)

#### Лабораторная работа №3
Создание веб-сервиса для получения/редактирования данных из вашей БД. Требуется разработать методы для основных (минимум трех) таблиц вашего приложения. Проверка в swagger/postman. 

Диаграмма компонентов+классов: компонент сервиса, интерфейс, структура модели по классам

Контрольные вопросы: веб-сервис, микросервисы, REST, RPC

* [Методические указания](https://github.com/iu5git/web-2022/blob/main/tutorials/lab3/lab3_tutorial.md)

#### Лабораторная работа №4
Базовая работа по фронтенду. Карточки элементов, навигация. Необходимо разработать страницы, аналогичные лабораторной работе №1 для просмотра услуг. Без взаимодействия с сервисом.

Навигация по двум страницам должна быть организована посредством самописной навигационной панели [Магазин]() / [Название услуги]()

На выбор `React`, `Vue`, `Angular`

Deployment диаграмма: узлы фронтенда, веб-сервиса, базы данных, web-сервера со статикой

Контрольные вопросы: react, props, компонент, элемент, состояние, хуки, жизненный цикл компонента

* [Методические указания](https://github.com/iu5git/web-2022/blob/main/tutorials/lab4/lab4_tutorial.md)

#### Лабораторная работа №5
Добавление Ajax-запросов, менеджера состояний redux. Подключение разработанного интерфейса фронтенда к веб-сервису из лабораторной №3

На выбор `React`, `Vue`, `Angular`

Sequence диаграмма: получение HTML страницы, AJAX запросы

Контрольные вопросы: AJAX, json, XmlHttpRequest, redux, контекст

* [Методические указания](https://github.com/iu5git/web-2022/blob/main/tutorials/lab4/lab4_tutorial.md)

#### Лабораторная работа №6
Добавление страницы просмотра для таблицы бронирований (корзина товаров, бронирования) и кнопки бронирования услуги. Из корзины товар можно удалить. Подключение к нужным сервисам. 

Добавление фильтрации и поиска на странице услуг:
1. По наименованию
2. По диапазону значений (цене). Максимальное и минимальное значение запрашиваются с сервера

Activity диаграмма: описание основного алгоритма, разделение на дорожки по элементам системы или ролям пользователей 

Контрольные вопросы: AJAX, json, XmlHttpRequest, react, props, компонент, элемент, состояние, веб-сервис, микросервисы, REST, RPC

#### Лабораторная работа №7
Таблица пользователей, авторизация, регистрация, хранение сессий, куки. Автозаполнение пользователя в таблице фактов при создании нового бронирования.

Диаграмма компонентов с детализацией бекенда: все компоненты системы с интерфейсами, выделить сервисы данных и авторизации 

* [Методические указания](https://github.com/iu5git/web-2022/blob/main/tutorials/lab7/lab7_tutorial.md)

Контрольные вопросы: куки, сессия

#### Лабораторная работа №8
Создание мобильного приложения с подключением к web-сервису. Просмотр 
услуг (товаров и тд), без бронирования и редактирования. 

* [iOS (Swift)](https://github.com/iu5git/web-2022/blob/main/tutorials/ios_tutorial/ios_tutorial.md)
* [Android (Java)](https://github.com/iu5git/web-2022/blob/main/tutorials/android_tutorial/android_tutorial.md)

## Домашнее задание
Добавление роли пользователя-менеджера контента, доработка под эту роль фронтенда и веб-сервиса:
1. Редактирование таблицы услуг
2. Изменение статусов таблицы бронирования
3. Фильтрация записей таблицы бронирования по дате и статусу. Список статусов начитывается с сервера

Доработка ролевой модели - ограничение прав на интерфейс для пользователь-клиента.

Добавить ограничение на вызовы методов веб-сервиса. Без авторизации менеджера в Insomnia должно быть доступно только чтение-получение данных через API 

#### Оформление единого отчёта 
Добавить диаграмму состояний для бронирований или услуг и диаграмму прецедентов.

Актуализировать все диаграммы из лабораторных, добавить краткое описание к диаграммам.

Пять разделов отчета: 
1. Введение (цель, задачи, актуальность)
2. Бизнес-процесс. Диаграмма прецедентов, диаграмма состояний
3. Архитектура. Диаграммы развертывания, ER с назначением таблиц и диаграмма компонентов с детализацией бекенда
4. Алгоритмы. Диаграмма последовательности и деятельности
5. Описание интерфейса. Перечень окон и их назначение

## Вопросы к экзамену
1. MVC
2. Django
3. Шаблонизация
4. HTTP
5. Web
6. HTML
7. URI
8. ORM
9. SQL
10. Модель и миграции
11. Веб-сервис
12. Сервис-ориентированная архитектура
13. Микросервисная архитектура
14. REST
15. RPC
16. AJAX
17. JSON
18. XmlHttpRequest
