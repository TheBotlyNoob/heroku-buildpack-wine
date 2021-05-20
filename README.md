# heroku-buildpack-wine

## This Is A Self Maintaining Repository!

A Heroku buildpack for wine that always downloads binary wine from a [static build](https://github.com/TheBotlyNoob/heroku-buildpack-wine/releases/latest/download/wine.tar.gz). It does not compile the wine within the dyno since it is time consuming.

## ***Usage***

## Stable Release Of Wine
```sh-session
heroku create myapp --buildpack https://github.com/TheBotlyNoob/heroku-buildpack-wine.git
```
**or**

[![Deploy](https://www.herokucdn.com/deploy/button.svg)](https://dashboard.heroku.com/new?button-url=https%3A%2F%2Fgithub.com%2FTheBotlyNoob%2Fheroku-buildpack-wine&template=https%3A%2F%2Fgithub.com%2FTheBotlyNoob%2Fheroku-buildpack-wine)

## Development Release Of Wine
```sh-session
heroku create myapp --buildpack https://github.com/TheBotlyNoob/heroku-buildpack-wine.git#dev
```
**or**

[![Deploy](https://www.herokucdn.com/deploy/button.svg)](https://dashboard.heroku.com/new?button-url=https://github.com/TheBotlyNoob/heroku-buildpack-wine&template=https://github.com/TheBotlyNoob/heroku-buildpack-wine/tree/dev)
