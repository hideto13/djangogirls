# Личный проект «DjangoGirls»

Проект личного блога с возможностью добавлять, редактировать и удалять посты

### Клонируйте репозиторий на свой компьютер

```
git clone https://github.com/hideto13/djangogirls.git
```

### Подготовьте виртуальное окружение

```
python -m venv venv
source venv/Scripts/activate
pip3 install -r requirements.txt
```

### Подготовьте базу данных

```
python manage.py migrate
```

### Запустите проект

```
python createsperuser
python runserver
```

Проект будет доступен по адресу http://127.0.0.1:8000/

Совершите вход в панель администратора с созданным суперпользователем http://127.0.0.1:8000/admin/ -
теперь доступно создавать, редактировать и удалять посты в блоге
