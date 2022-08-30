docker build . -t app:v1

docker run --name app -d -p 8080:8080 app:v1
