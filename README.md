# heroku-buildpack-wine

A Heroku buildpack for wine that always downloads binary wine from a [static build](https://github.com/iScribes/heroku-buildpack-wine/releases/download/1.6/wine1.6.tar.gz). It does not compile the wine within the dyno since it is time consuming.

## Usage
Add the following to `.buildpacks`:

```
https://github.com/TheBotlyNoob/heroku-buildpack-wine.git
```
