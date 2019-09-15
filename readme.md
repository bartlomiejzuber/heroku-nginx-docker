# Heroku NGINX Docker setup

Heroku config example with docker & nginx.

1. `docker build -t web .`
2. `heroku container:push web --app <APPNAME>`
3. `heroku container:release web --app <APPNAME>`