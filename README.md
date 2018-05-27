# django-space-social-project


>django: 2.0 
>python: 3.6 
>sqlite3


conda create --name MyDjangoEnv python=3.6
conda info --envs
conda install django
source activate MyDjangoEnv (启动)
django-admin startproject demo (主project)
python manage.py runserver （运行）
python manage.py startapp first_app (app页面)
python manage.py migrate (更新app配置)
python manage.py makemigrations blog (更新model)
python manage.py createsuperuser (创建admin)

1.  pip install Faker
2.  pip install django-bootstrap3
3.  pip install misaka
4.  pip install django-braces
