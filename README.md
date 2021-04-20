Tutorial
https://www.youtube.com/watch?v=xxjzwdtWozI

source bin/activate
pip install django
django-admin startproject proj4
python manage.py runserver

docker-compose up
docker-compose down
docker-compose up --build
docker-compose up -d
docker-compose logs
docker-compose exec web python manage.py migrate
docker-compose exec web python manage.py createsuperuser (andre 1234)



sudo groupadd docker
sudo usermod -aG docker $USER
docker run hello-world
sudo systemctl enable docker.service
sudo systemctl enable containerd.service
newgrp docker
docker run hello-world




