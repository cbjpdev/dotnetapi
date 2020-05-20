docker build -t mymicroservice .
docker images
docker run -it --rm -p 3000:80 --name mymicroservicecontainer mymicroservice
docker ps
docker login
docker tag mymicroservice [YOUR DOCKER USERNAME]/mymicroservice
docker push [YOUR DOCKER USERNAME]/mymicroservice