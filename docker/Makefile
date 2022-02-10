VERSION=3.5.9-0
PROJECT=emresaglam

all: build

build:
	docker build -t ${PROJECT}/kubernetes-zookeeper:${VERSION} .

push: build
	docker -- push ${PROJECT}/kubernetes-zookeeper:${VERSION}

.PHONY: all build push
