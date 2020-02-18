# Contoh penerapan Docker pada web HTML landing page sekolah devops cilsy


## Step by step
#
#
###  ~masuk kedalam file hasil clone/pull
###### $cd lending-page-HTML
#
### ~generate Docker image
###### $docker image build -t iddochub/nginx:version directory/Dockerfile
###### $docker image build -t heryslty/nginx:latest .
#
### ~generate and run docker container
###### $docker run -d -p port_masking:port_dalam_container --name nama_container_yang_mau_dibuat docker_image_yang_akan_dijalankan_containernya
###### $docker run -d -p 8082:80 --name container1 heri-xxx
#
### Buka Pada browser ip:port atau loclhost:port
##### localhost:8082

