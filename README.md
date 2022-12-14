Проект планировщика задач

#### Стэк используемых технологий:

* Python 3.10
* Django 4.0.5
* PostgreSQL

Для запуска проекта клонируйте репозиторий и установите зависимости:

pip install -r requirements.txt

Создайте в корне проекта файл .env и укажите значения констант:

* DEBUG
* DATABASE_URL
* SECRET_KEY
* SOCIAL_AUTH_VK_OAUTH2_KEY
* SOCIAL_AUTH_VK_OAUTH2_SECRET
* BOT_TOKEN

Чтобы запустить приложение воспользуйтесь командой docker-compose up -d

### Этапы выполнения работы:

Шаг 1:

Подготовка проекта и настройка необходимых системных компонентов для дальнейшей работы.

Шаг 2:

Настройка локальной разработки с помощью Docker Compose и автоматического деплоя всего приложения на сервер по пушу в
GitHub.

Шаг 3:

Реализованы методы API, описанных в документации swagger. Аутентификация и авторизация. Авторизация через VK с помощью
OAuth2.0.

Шаг 4:

Реализована возможность добавления категорий, целей и комментариев к ним. Сортировка целей по дате дедлайна и
приоритету.

Шаг 5:

Добавлены доски с целями и возможность шеринга досок между участниками.

Шаг 6:

Добавлен телеграм-бот. Просмотреть свои цели и запланировать новые можно с помощью бота: @sky_todolist_bot