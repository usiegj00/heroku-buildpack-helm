# Heroku buildpack for Kappy instance

## Helm binary
1. Make sure to have a `.helm_version` file at the root of your project, for example

```
v2.14.0
```

2. Add this buildpack to the heroku project

```
heroku buildpacks:add https://github.com/moovweb/heroku-buildpack-kappy
```
