# Django-Email-Async-Reader

## Проект является выполнением тестового задания на вакансию Backend-разработчик в COMSOFTLAB.

## Демонстрация работы

### Чтение сообщений:
![Чтение сообщений](https://s1.gifyu.com/images/SO1ef.gif)

### Загрузка импортированных сообщений:
![Загрузка сообщений](https://s1.gifyu.com/images/SOA2T.gif)

### Скачивание вложенных к сообщению файлов:
![Скачивание файлов](https://s1.gifyu.com/images/SOA23.gif)

### После прочтения, импортированные сообщения загружаются быстрее:
![Загрузка импортированных сообщений](https://s11.gifyu.com/images/SOA2q.gif)

## Для запуска клонируем репозиторий и в корневой папке проекта запускаем команду:
```
docker compose up
```
### Следующий этап - загрузка данных от почты в базу данных:
После успешного запуска контейнера переходим по адресу **http://localhost/admin** и авторизуемся как ***admin:admin***.
В админ-панели добавляем экземпляр модели TargetEmail, где указываем почту, пароль приложения, а также выбираем используемый сервис:
![Импортирование данных от почты в базу данных](https://s1.gifyu.com/images/SOA2L.jpg)

### Сервис готов к работе.
