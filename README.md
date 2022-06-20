# dockerprojectcpp

// create the docker image
docker build .

// create the docker image with repository name and tag name 
docker build -t mydockerrepository:mydockertag .

// run the container
docker run imageid

// remove the container
docker rm containerid