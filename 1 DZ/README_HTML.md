# Заменa страницу приветсвия Nginx

Для замены страницы приветсвия Nginx через консоль нам необходимо:

1. Установить Docker Desktop с официального сайта: https://docs.docker.com/get-docker/
2. Открыть консоль и запустить Docker:

```
ocker run -d -p 80:80 nginx
```
3. Затем создать каталог в который необзодимо положить файл 

```
index.html
```
4. Набираем команду 

```
docker run -d -p 80:80 -v ${PWD}:/usr/share/nginx/html --name=my_proba nginx
```
5. Переходим в браузер и проверяем:

```
localhost
```