
# Run following command on terminal

docker build --tag=hellodocker .

docker image ls

docker run -p 4000:80 hellodocker
docker run -d -p 4000:80 hellodocker
docker run ---detach --publish 4000:80 hellodocker

<!-- you can also change the port 4001:80 it will create a new virtual machine running can be communicate to each other -->
<!-- those command are the same aboved-->

docker container stop CONTAINER_ID
docker rm CONTAINER_ID

docker container ls