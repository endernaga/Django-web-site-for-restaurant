# Restaurant kitchen service
> created for mate academy
https://restaurant-kitchen-service2-0.onrender.com
### Credentials
```
login: user
password: user12345
```

## Installing / Getting started

A quick introduction of the minimal setup you need to get a hello world up &
running.

```
pip install -r -requirements.txt
```

### Initial Configuration

required env arguments as :
>DATABASE_URL; DJANGO_DEBUG; DJANGO_SECRET_KEY;

## Developing

Here's a brief intro about what a developer must do in order to start developing
the project further:

```shell
git clone [https://github.com/your/awesome-project.git](https://github.com/endernaga/restaurant-kitchen-service2.0/tree/master)
```

### Deploying / Publishing
```
./ build.sh
gunicorn restaurant.wsgi:application
```
