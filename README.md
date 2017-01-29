Example supports `Django 1.10`.

```
pip install social-auth-app-django
```

Configure your app id and secret in `settins.py`:

```
SOCIAL_AUTH_FACEBOOK_KEY = 'REPLACE WITH YOUR APP ID'
SOCIAL_AUTH_FACEBOOK_SECRET = 'REPLACE WITH YOUR APP SETTING'
```

For details how to get them see and configure Facebook app See https://maketips.net/tip/129/django-social-auth-demo 

Run example on `djsoc.local` domain:

```
echo "127.0.0.1 djsoc.local" >> /etc/hosts
python manage.py migrate
manage.py runserver djsoc.local:8000
```
