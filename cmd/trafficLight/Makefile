# make traffic
.PHONY: default image

default: image

image: bin
	docker build -t jiulongzaitian/traffic-light:v1.1 .
	docker push jiulongzaitian/traffic-light:v1.1

.PHONY: bin
bin:
	go build -o light

.PHONY: run 
run: bin
	./led


