# Neobis_DjangoGirls_Project
___
# Описание проекта
В проекте реализована возможность вести свой блог.
Из функционала: добавление, удаление, изменение своего поста

# Установка
* Склонируй репозиторий используя команду
```
git clone git@github.com:31nkmu/Neobis_ToDo_Project.git
```
* Создай виртуальное окружение используя команду
```
python3 -m venv <name of your environment> 
```

* Активируй виртуальное окружение
``` 
source <name of your environment>/bin/activate 
```

* Установи зависимости
``` 
pip install -r requirements.txt 
```

* Создай .env файл
```
touch .env
```

* Запиши данные в файл .env (смотри пример в файле evn_example)

* Сделай миграции
```
  ./manage.py migrate
```
* Запусти свой проект
``` 
./manage.py runserver 
или
 python3 manage.py runserver 
``` 
---
