APACHE_VERSION ?= 2.4.20
PHP_VERSION ?= 5.6.22
DOCKER_USER ?= mumoshu
DOCKER_IMAGE ?= apache-php

build:
	docker build -t $(DOCKER_USER)/$(DOCKER_IMAGE):$(APACHE_VERSION)-$(PHP_VERSION) .

sh:
	docker run -it --rm $(DOCKER_USER)/$(DOCKER_IMAGE):$(APACHE_VERSION)-$(PHP_VERSION) sh
