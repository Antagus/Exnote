# Excellent Note Desk
## Инструкция для запуска

### Установка клиентской части

1. Необходимо установить NodeJS версиии 18.16 и не младше: https://nodejs.org/en
2. После установки NodeJS установит менеджер пакетов командой npm
3. Скачиваем или клонируем репозиторий
4. Открываем консоль и переходим в папку с проектом, после чело прописываем npm install, для установки всех необходимых библиотек (они скачаются и установятся автоматически)
5. После чего прописываем в консоли npm start (в этой же папке)
6. Клиентская часть проекта запуститься

### Установка серверной части

База данных:

1. С помощью любой СУБД в моем случае HediSQL, открываем новую сессию на локальном порту
2. устанавливаем название учетной записи root и пароль root
3. Импортируем базу данных из папки SourseBase файл называет base.sql

Сервер:

1. Открываем папку server в консоли
2. Прописываем npm install, для установки библиотек
3. прописываем npm start и приложение запуститься, с сообщением, что запущено на 5000 порту, если на вашем ПК порт занят, в index.js в папке server, в самом начале есть строка конфигурации подключения, в нем вы можете указать свои данные.

## Предисловие

Спасибо за вашу рецензию! А. Гусев
