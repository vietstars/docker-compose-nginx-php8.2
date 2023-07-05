### check ox
cat /etc/os-release

#### nginx on linux:debian-12

### not daemon 
docker ps -a --no-trunc 
docker restart ID
### run background
docker run -it --entrypoint /bin/sh nginx-web