docker exec -it e377f30dfcd4 bash

docker cp wine.csv e377f30dfcd4://home/jovyan/wine.csv

docker run -p 8888:8888 jupyter/scipy-notebook:17aba6048f44

docker run -v /Users/whoisapunk/Desktop/docker_works/jupyter_notebook:/home/jovyan/ -p 8888:8888 jupyter/scipy-notebook:17aba6048f44



docker build .
docker build -t my_notebook .

#запускаем контейнер с Dokerfile (  .  )
docker run -v /Users/whoisapunk/Desktop/docker_works/jupyter_notebook:/home/jovyan/ -p 8888:8888 5c51c08a3eb8 #вставляем id контейнера или имя


docker-compose up

docler-compose down  #delete