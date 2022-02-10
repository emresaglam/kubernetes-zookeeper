VERSION=3.5.6-0
PROJECT=vmakoto

all: build

build:
	docker build -t ${PROJECT}/kubernetes-zookeeper:${VERSION} .

push: build
	docker -- push ${PROJECT}/kubernetes-zookeeper:${VERSION}

.PHONY: all build push
