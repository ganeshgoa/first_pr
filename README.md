# first_pr

Данный сервис работает на стеке Django + Postgresql. 

Для того чтобы запустить этот код, необходимо указать поднять сервер на Postgresql, указать имя сервера, IP-адрес. 
Сделать это необходимо во вкладке DjangoAPI/settings.py:
DATABASES = {
    'default': {
        'ENGINE': 'django.db.backends.postgresql',
        'NAME': 'mytestdb', - указываем имя сервера
        'USER': 'postgres', - имя пользователя
        'PASSWORD': 'xxxxx', - пароль
        'HOST': '127.0.0.1', - ip-адрес хоста
        'PORT': '5432' - номер порта 
    }
}
