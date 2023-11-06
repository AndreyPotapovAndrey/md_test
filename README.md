# Задача №1:
## Папка nginx_task1:
<span style="background-color:grey">**_docker build -t my_nginx:v1 -f nginx_dockerfile . _**</span> Сборка контейнера<br>
<br>
<span style="background-color:grey">**_docker run -p 8000:80 my_nginx:v1 _**</span> Запуск контейнера<br>
<br>
(http://localhost:8000/) Проверка через браузер<br>
<br>
<br>
# Задача №2:
## Папка django_task2:
<span style="background-color:grey">**_docker build -t my_django:v1 _** Сборка контейнера</span><br>
<br>
<span style="background-color:grey">**_docker run -d -p 8000:8000 my_django:v1 _** Запуск контейнера в фоновом режиме</span><br>
<br>
(http://localhost:8000/api/v1/) Проверка через браузер