##From root with docker-compose:
docker-compose up


 ##In baseapp-back:

docker build -t baseapp-back .
docker run -d -p 8000:8000 baseapp-back -i


##In baseapp-front:

docker build -t baseapp-front .
docker run -d -p 3000:80 baseapp-front
