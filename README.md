# docker
Useful docker commands
docker pull
docker images
docker ps -a
docker run --name collections-dev -p 3306:3306 -e MYSQL_ROOT_PASSWORD=root -d mysql
docker start collections-dev
The -p (or –publish) option is used to explicitly specify port mappings when running a Docker container. It allows you to map a specific port on the host system to a specific port inside the container. The syntax for using -p is -p <host_port>:<container_port>.
