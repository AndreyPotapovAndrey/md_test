# Задача №1:
## Папка nginx_task1:
docker build -t my_nginx:v1 -f nginx_dockerfile . Сборка контейнера<br>
docker run -p 8000:80 my_nginx:v1 Запуск контейнера<br>
(http://localhost:8000/) Проверка через браузер<br>
<br>
# Задача №2:
## Папка django_task2:
docker build -t my_django:v1 Сборка контейнера<br>
docker run -d -p 8000:8000 my_django:v1 Запуск контейнера в фоновом режиме<br>
(http://localhost:8000/api/v1/)