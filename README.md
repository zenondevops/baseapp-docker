In baseapp-back:

docker build -t baseapp-back .
docker run -d -p 8000:8000 -v $(pwd)/log:/app/log baseapp-back