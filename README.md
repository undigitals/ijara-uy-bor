## Projectni ishlatish uchun:

### O'rnatilishi kerak bo'lgan paketlar(kutubxonalar):

Avval `python` o'rnatilgan yoki yo'qligini aniqlang.



### Database (postgresql)

`ijarabor/settings.py`

```py
DATABASES = {
    'default': {
        'ENGINE': 'django.db.backends.postgresql',
        'NAME': 'dbname',
        'USER': 'postgres',
        'PASSWORD': 'password',
        'HOST': 'localhost'
    }
}
```
`postgreSql` da database yaratib yoqoridagilarni yangilang.

### Komandalar

`venv` virtual muhitni ishga tushirish:

```py
    source ./venv/bin/activate
```

Serverni ishga tushurish:

```py
    python manage.py runserver
```