# cash-manager-ci

## Clone the Project

To clone and update your project on your machine:

* Initialize all submodules:

```
  git clone git@github.com:dupuysylvain/cash-manager-ci.git
  cd cash-manager-ci
  git submodule update --init --recursive --remote
```
  
* Update all sub projects (api and mobile):

```
  git submodule foreach git pull origin master
  git submodule foreach git checkout master
```

## Run docker

```
docker-compose up
```

> When all dockers are up, you can access to the api at `localhost:8080` and get the apk on `localhost/cashmanager.apk`