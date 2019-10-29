VERSION=2.3.1-0
PROJECT=vmakoto

all: build

build:
	docker build --pull -t ${PROJECT}/kubernetes-kafka:${VERSION} .

push: build
	docker -- push ${PROJECT}/kubernetes-kafka:${VERSION}

.PHONY: all build push
