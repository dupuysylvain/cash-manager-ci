# cash-manager-ci

## Clone the Project

To clone and update your project on your machine:

* Clone the project:

```
  git clone git@github.com:dupuysylvain/cash-manager-ci.git
```
  
* Go into the project folder:

```
  cd cash-manager-ci
```
  
* Initialize all submodules:

```
  git submodule update --init --recursive --remote
```
  
* Update all files and checkout to a specific branch:

```
  git submodule foreach git pull origin master
  git submodule foreach git checkout master
```
