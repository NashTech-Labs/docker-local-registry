# Dockerhub Registry
Docker hub is the Image Repository with numbers of Official Images ready to use. It is easy way to push your own images to the Docker Hub registry so that everyone can uesd from your Dockerized applications.

# local Registry:
But in some cases, you not want to push your images outside of your registry. So you can set up a local registry.

# Prerequisites:
* Docker account.
* And running Docker locally.

After push the image you can delete the tag image.
using- sudo docker rmi localhost:5000/nginx
check sudo docker images 
pull the image on local registry:
* sudo docker pull localhost:5000/nginx

# Execute:
sudo chmod +x local-registry
./local-registry

# registry logs
sudo docker logs -f local-registry