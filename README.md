# Heroku buildpack with Helm binary in PATH

Note this version uses the updated binary download location [get.helm.sh](https://get.helm.sh).

## Usage
1. Make sure to have a `.helm_version` file at the root of your project, for example

```
v3.14.0
```

2. Add this buildpack to your heroku project

```
heroku buildpacks:add https://github.com/usiegj00/heroku-buildpack-helm
```
