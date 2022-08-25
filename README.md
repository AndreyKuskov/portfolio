# Сайт-портфолио

Сам сайт находится по адресу: andreykuskov.ru

## Installation

Клонировать репозиторий в любую папку

```bash
git clone https://github.com/AndreyKuskov/portfolio.git
```

Создать виртуальное окружение

```bash
python3 -m venv env
```

или 

```bash
python -m venv env
```

Активировать виртуальное окружение

```bash
. env/bin/activate
```

Перейти в папку проекта и выполнить команду

```bash
pip3 install -r requirements.txt
```

Далее необходимо создать миграции для моделей приложения

```bash
python3 manage.py makemigrations resume
```

Проводим миграции

```bash
python3 manage.py migrate
```

Запускаем проект
```bash
python3 manage.py runserver
```

## FAQ

**Могу ли я взять себе этот сайт?**

Конечно можешь, Front-End составляющая очень красивая!

**Могу ли я спросить у тебя, как сайт работает?**

Да! Напиши мне по одному из адресов, указанных на самом сайте или на почту ниже.

## Email

andrey.kuskov.05@gmail.com