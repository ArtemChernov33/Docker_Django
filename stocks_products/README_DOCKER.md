# Запуск приложениия "Склады и товары" в Docker

1. Клонируем репозиторий 

```
https://github.com/ArtemChernov33/DockerFile.git
```
2. Собираем контейнер с помощью команды:

```
docker build . --tag=my_chegototam_1.1
```
3. Запускаем Docker:

```
docker run -p 8030:8000 my_chegototam_1.1
```

4. В браузере в поисковой строке вводим 

```
http://localhost:8030
```