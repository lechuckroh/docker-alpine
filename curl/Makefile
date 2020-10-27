IMAGE_URI=lechuckroh/alpine-curl

.PHONY: build
build:
	@docker build -t $(IMAGE_URI):latest .

.PHONY: push
push:
	@docker push $(IMAGE_URI):latest

.PHONY: rmi
rmi:
	@docker rmi $(IMAGE_URI):latest
