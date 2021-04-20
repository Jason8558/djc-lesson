Болванка проекта

1. Склонировать проект - **git clone** (либо **ssh** ссылка, либо **https**)
2. Перейти в директорию **djchannels-rtc**
3. Установить виртуальное окружение (например через venv)

Например: `python3 -m venv myenv`

И активировать: _Windows_ (**myenv\Scripts\activate**), _unix_ (**source myenv/bin/activate**)

4. Установить зависимости - `pip install -r requirements.txt`
5. Запустить `python manage.py migrate`
6. Запустить `python manage.py loaddata data.json --app=posts`, чтобы предзаполнить БД
7. Запустить `python manage.py loaddata data.json --app=comments`, чтобы предзаполнить БД



Для тех, кто хочет склонировать готовую версию проекта, - используйте команду **git clone --branch completed-project git@gitlab.com:PyCoding1/djchannels-rtc.git** (или `https://gitlab.com/PyCoding1/djchannels-rtc.git`)

**ВНИМАНИЕ!** README.md файл в ветках _master_ и _completed-project_ **различаются**!

Логин и пароль от админки - **admin/devpass**
