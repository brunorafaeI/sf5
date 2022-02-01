
# Symfony 5 - CI/CD

A simple project built with Symfony framework in version 5.4 and PHP 7.4 in order to explore the new model of folder and documents structure, as well as the use of CI/CD from github.


## Getting Started

To start this project you need execute this command :

```bash
  docker-composer up -d
```
Connect to the docker's container:
```bash
  docker exec -it sf5_app_1 bash
```
And install all composer's dependencies :
```bash
  cd backend && composer install
```