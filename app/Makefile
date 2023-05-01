.DEFAULT_GOAL := build-run

clean:
	./gradlew clean

build:
	./gradlew clean build

install:
	./gradlew clean install

run-dist-h:
	./build/install/app/bin/app -h

run-dist:
	./build/install/app/bin/app

run:
	./gradlew run

test:
	make -C app test

report:
	make -C app report

lint:
	./gradlew checkstyleMain
# 	 checkstyleTest

update-deps:
	make -C app update-deps


build-run: build run

.PHONY: build
