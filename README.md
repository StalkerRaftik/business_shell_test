# Техническое задание

## Стек технологий
### Backend:
`Django`, `Django Rest Framework`

### Frontend:
На ваш выбор:

`React`, `React Router`, `Axios`

или

`Vue`, `Vue Router`, `Axios`

Приветствуется использование различных дополнительных инструментов, как то: готовые UI-компоненты, библиотеки, фреймворки и т.д.

## Описание проекта
Необходимо создать сайт-блог, на главной странице которого будет отображаться список постов. 
Администраторы сайта могут создавать новые посты.
При нажатии на пост пользователь будет перенаправлен на отдельную страницу, где будет отображаться 
выбранный пост и комментарии, оставленные под ним. Комментарии могут оставлять любые зарегистрировавшиеся пользователи.


## Технические требования

### Backend
- Разработка модели `Post` для представления поста.
- Разработка модели `Comment` для представления комментария.
- Разработка API для выполнения следующих действий:
  - Создание нового поста(только для администратора)
  - Получение списка всех постов.
  - Получение конкретного поста и связанных с ним комментариев.
  - Создание нового комментария под определенным постом(только для зарегистрированных пользователей).
  - Аутентификация и авторизация пользователей (вход, регистрация).

Апи должен реализовываться с помощью Django Rest Framework. 
Входящие и исходящие данные должны быть провалидированы 
с помощью валидаторов из Django Rest Framework

### Frontend
- Создание главной страницы со списком постов и формой создания нового поста. Форму должны видеть только администраторы.
- Создание отдельной страницы для отображения выбранного поста и связанных с ним комментариев, а также форма для создания нового комментария(показывать только для зарегистрированных пользователей).
- Реализация компонента `хэдера`, позволяющего пользователю войти или зарегистрироваться как гость.
- Интерактивность: при нажатии на пост на главной странице, пользователь должен быть перенаправлен на страницу выбранного поста.

## Дизайн и интерфейс
- Макет сайта должен быть минималистичным, с фокусом на функциональности.
- Использование простого и интуитивно понятного дизайна.
- Не нужно добавлять излишний функционал, который не перечислен пунктами выше.



## Оформление проекта для сдачи
1. Необходимо создать `README.md` документ, в котором будут описаны шаги 
запуска сайта на компьютере проверяющего.
2. Загрузить готовый проект на `GitHub`.
3. Написать письмо на почту `business-shell@yandex.ru` с заголовком `Техническое задание`, прикрепив в теле письма ссылку на проект и ваши контакты в Telegram

## Комментарий от автора задачи
Лучший код - ненаписанный код. А поэтому:
1. Советую посмотреть готовые библиотеки для Django-авторизации, чтобы не писать самому этот функционал.
2. На фронт есть множество ui-библиотек, которые можно использовать, чтобы избежать лишней верстки(MUI, Vuetify, Bootstrap и т.д.) 

## Обучающие материалы и ссылки на библиотеки:
### Backend
1. Django
   1. https://docs.djangoproject.com/en/4.2/
   2. https://www.youtube.com/playlist?list=PLA0M1Bcd0w8xO_39zZll2u1lz_Q-Mwn1F
2. Django Rest Framework
   1. https://www.django-rest-framework.org/
   2. https://www.youtube.com/playlist?list=PLA0M1Bcd0w8xZA3Kl1fYmOH_MfLpiYMRs/

### Frontend
1. Vue
   1. https://vuejs.org/guide/introduction.html
   2. https://www.youtube.com/watch?v=XzLuMtDelGk
2. Vue Router
   1. https://router.vuejs.org/guide/


1. React
   1. https://react.dev/learn
   2. https://www.youtube.com/watch?v=GNrdg3PzpJQ
2. React Router
   1. https://reactrouter.com/en/main