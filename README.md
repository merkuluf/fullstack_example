# Git Репозиторий: fullstack_example

Этот репозиторий содержит два приложения - клиент и сервер.

## Сервер

Сервер написан на Node Express и взаимодействует с локальной базой данных MongoDB для регистрирации пользователей.
Ввод валидируется через middleware. Есть возможность добавления аватара, сохранив его на сервере - формируется ссылка, которую позднее при регистрации сервер сохраняет в модель юзера.
API написано по концепции REST.

### Запуск сервера

Чтобы запустить сервер, выполните следующие шаги:

1. `git clone github.com/merkuluf/fullstack_example`
2. `cd fullstack_example/server`
3. `npm install`
4. `node server.js`

## Клиент

Клиент разработан с использованием React JS + Redux.
В основном используются кастомные решения и чистый CSS.

### Запуск клиента

Для запуска клиента следуйте указанным выше шагам.

Для режима разработки:

1. `cd fullstack_example/client`
2. `npm install`
3. `npm run dev`

Для сборки в продакшн:

1. `cd fullstack_example/client`
2. `npm install`
3. `npm run build`
