# build and push images to dockerhub

```sh
 # Create Docker Image
 $ docker build -t sip-serviceregistry .
 # Publish Docker container to Docker Hub
 $ docker tag sip-serviceregistry ziedab/sip-serviceregistry
 $ docker push  ziedab/sip-serviceregistry

 # Create Docker Image 
 $ docker build -t sip-serviceproxy .
 # Publish Docker container to Docker Hub
 $ docker tag sip-serviceproxy ziedab/sip-serviceproxy
 $ docker push  ziedab/sip-serviceproxy
 
 # Create Docker Image 
 $ docker build -t sip-serviceprovider .
 # Publish Docker container to Docker Hub
 $ docker tag sip-serviceprovider ziedab/sip-serviceprovider
 $ docker push  ziedab/sip-serviceprovider

 # Create Docker Image
 $ docker build -t sip-servicearticle .
 # Publish Docker container to Docker Hub
 $ docker tag sip-servicearticle ziedab/sip-servicearticle
 $ docker push  ziedab/sip-servicearticle
```

# useful urls

- **http://localhost:8001/providers/**:  [link](http://localhost:8001/providers/)
- **http://localhost:8003/articles/**:  [link](http://localhost:8003/articles/)
- **http://localhost:9092/providers/**:  [link](http://localhost:9092/providers/)
- **http://localhost:9092/articles/**:  [link](http://localhost:9092/articles/)

# Docker compose[up & run/down]

```sh
$ docker compose up -d
$ docker compose down -v
```
