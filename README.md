# nsq-golang-docker-tutorial

NSQ demo repo to try out messaging with NSQ & Go

## Run NSQ with Docker Compose

Start NSQ (the patterns below will integrate with this cluster)

	docker-compose -f docker-compose-nsq.yml up

Browse to the admin UI: http://localhost:4171/


## Examples
    
build a docker container with our consumer app in it
    
  docker build -t nsq-consumer -f Dockerfile-consumer .
