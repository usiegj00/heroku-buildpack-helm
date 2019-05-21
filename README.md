# Heroku buildpack with Helm binary in PATH

## Usage
1. Make sure to have a `.helm_version` file at the root of your project, for example

```
v2.14.0
```

2. Add this buildpack to your heroku project

```
heroku buildpacks:add https://github.com/moovweb/heroku-buildpack-helm
```
