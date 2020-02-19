# README
Contoh penerapan Docker pada web HTML landing page sekolah devops cilsy


## How To Use
* masuk kedalam file hasil clone/pull
```
cd lending-page-HTML
```
* Build Docker image
```
docker image build -t iddochub/nginx:version directory/Dockerfile
docker image build -t heryslty/nginx:latest .
```
* Run docker container
Contoh command `docker run -d -p port_masking:port_dalam_container --name nama_container_yang_mau_dibuat docker_image_yang_akan_dijalankan_containernya`
```
docker run -d -p 8082:80 --name container1 heri-xxx
```
* Buka Pada browser ip:port atau loclhost:port
```
curl localhost:8082
```
