# docker-file-transfer

Instructions:

Docker Build:
docker build --tag sanjeev-file-transfer:2.0 .

Docker Run:
docker run --publish 22:22 --detach --name sanjeev-file-transfer sanjeev-file-transfer:2.0

Bash Commands:
docker exec -it sanjeev-file-transfer bash

Docker Publish:
docker tag sanjeev-file-transfer:2.0 lnschitikela/sanjeev-file-transfer:2.0

docker push lnschitikela/sanjeev-file-transfer:2.0