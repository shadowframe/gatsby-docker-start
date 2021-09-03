# Gatsby DOCKER STARTER
## Startet nginx, aber kein autoupdate
## https://typeofnan.dev/how-to-serve-a-gatsby-app-with-nginx-in-docker/


## CMD

docker build -t gatsby-nginx .

docker run --rm -it -p 8080:80 gatsby-nginx

