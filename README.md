0. Clone this repository and the others or just this one.

git clone https://github.com/ethi0/1c_server.git

git clone https://github.com/ethi0/1c_server_data.git

git clone https://githib.com/ethi0/1c_db.git
1. Build all images or pull them from DockerHub:

docker pull ethi0/1c_server

docker pull ethi0/1c_server_data

docker pull ethi0/1c_db

2. Initialize containers and start them:
docker-compose up -d

3. docker-compose stop/start.

Or... Just clone this repo, cd to it and:
docker-compose up -d
