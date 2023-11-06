# Задача №1:
## *Папка nginx_task1:*
*  **docker build -t my_nginx:v1 -f nginx_dockerfile ._**   Сборка контейнера
* **docker run -p 8000:80 my_nginx:v1 _**  Запуск контейнера
* (http://localhost:8000/) Проверка через браузер

# Задача №2:
## *Папка django_task2:*
* **docker build -t my_django:v1 _** Сборка контейнера

* **docker run -d -p 8000:8000 my_django:v1 _** Запуск контейнера в фоновом режиме

* (http://localhost:8000/api/v1/) Проверка через браузер