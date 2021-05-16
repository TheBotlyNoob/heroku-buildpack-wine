# heroku-buildpack-wine

## This Is A Self Maintaining Repository!

A Heroku buildpack for wine that always downloads binary wine from a [static build](https://github.com/TheBotlyNoob/heroku-buildpack-wine/releases/latest/download/wine.tar.gz). It does not compile the wine within the dyno since it is time consuming.

## Usage
Add the following to `.buildpacks`:

```
https://github.com/TheBotlyNoob/heroku-buildpack-wine.git
```
