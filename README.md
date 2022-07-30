Para deploy no Heroku

Fazer login

## cria app
heroku create <nome do app>

## cria banco
heroku addons:create heroku-postgresql:hobby-dev --app <nome do app>

## ve config do app
heroku config --app <nome do app>