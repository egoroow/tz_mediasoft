# База фильмов

## Задачи
* См. Общие требования; записью являются фильм, актер, режиссер, жанр
* Пользователь может указывать актеров и режиссеров (выбор из существующих и добавление новых)
* Пользователь может просматривать список фильмов, в которых принимал участие актер / снимал режиссер
* Пользователь может оценить фильм - необходимо отображать оценку и количество оценивших
Опционально:
* Отображать рейтинги IMDB/Кинопоиск
* Добавлять рецензии к фильмам
* Добавлять постеры к фильмам

### Общее описание

#### 1. Приложение
Задание реализовано на языке Python, при помощи фреймворка Django

Файлы миграций БД находятся внутри проекта

Для верстки использовался bootstrap

#### 2. Как запустить проект
Скачать проект из репозитория

Перейти в директорию проекта, после перейти в директорию виртуального окружения

```bash
cd venv\Scripts\
```

Активировать виртуальное окружение командой

```bash
activate
```

Вернуться в директорию mediasoft1, запустить проект командой

```bash
python manage.py runserver
```

Данные для входа в админ панель

* login: febest
* password: 1

Для запуска требуется установленный Python 3.8+

### Разработчик
Исаков Егор УлГТУ
