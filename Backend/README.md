# node-docker
Simple node and express docker 

run following commands to create an image
// build the image
$ docker build -t start-dok/simple-backend .
//check if the image has build
$ docker images
Run the project in localhost
$ docker run -p 4000:4000 start-dok/simple-backend
// list all the images in docker
$ docker ps
// stop a container
$ docker stop xxxxx
// remove an image
$ docker rmi xxxxx
