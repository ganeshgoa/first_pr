# RESTapi Django+Postgresql

1 Download project 
2 Start new postgresql server or use exist 
    copy server name, username, passwoed, ip address(host), port
    and insert to page DjangoAPI/settings.py:
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

3 Then compile code 
Now you can use GET, POST, DELETE, UPLOAD files on database 
