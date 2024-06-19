```
cd Docker
create a .env file following demo.env

for backend
* sudo docker compose -f docker-compose-dev-be.yml build
* sudo docker compose -f docker-compose-dev-be.yml run --rm backend python manage.py migrate
* sudo docker compose -f docker-compose-dev-be.yml up

  ----- for add new package ------
* sudo docker compose -f docker-compose-dev-be.yml run --rm backend poetry add <package_name>


for frontend
* sudo docker compose -f docker-compose-dev-fe.yml build
* sudo docker compose -f docker-compose-dev-fe.yml up
  ----- for add new package ------
* sudo docker compose -f docker-compose-dev-fe.yml run --rm frontend yarn add <package_name>
````
