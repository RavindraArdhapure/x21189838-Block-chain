## Docker Hub URL for Image ##
```https://hub.docker.com/repository/docker/ravindraardhapure1995/x21189838```

## Pull an Image from Docker Hub ##
```docker pull -- ravindraardhapure1995/x21189838:latest```

## Run an image ##

```docker run --name  x21189838 -p 8090:8080 x21189838```

## Build an Image from Dockerfile ##

```docker build --tag x21189838 .```

## Run an image ##

```docker run --name  x21189838 -p 8090:8080 x21189838```

## Run the curl command ##

This transfers ETH:

```curl --header "Content-Type: application/json" --request POST --data '{"address":"0xac4FafdA6A3A6B48b4cDC2a896acf8D104C81d6C", "amount":"0.05"}' http://localhost:8090/eth```

This transfers token:

```curl --header "Content-Type: application/json" --request POST --data '{"address":"0xac4FafdA6A3A6B48b4cDC2a896acf8D104C81d6C"}' http://localhost:8090/token```

