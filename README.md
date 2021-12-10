<h1 align="center">Django-fusion</h1>

### :gear:Construção
```bash
git clone https://github.com/isaias0rt0n/django-fusion.git
```
```bash
cd fusion
```
Rodando a aplicação em docker(configurar database no settings.py)
```bash
docker-compose up -d
```
Realizando migrations
```bash
docker-compose exec web python manage.py makemigrations && docker-compose exec web python manage.py migrate
```

### :pushpin: [Aplicação no Heroku](https://fusion-icc.herokuapp.com/)
