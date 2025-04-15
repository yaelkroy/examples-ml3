
help:
	cat Makefile
run:
	docker-compose up
exec:
	docker-compose exec examples-ml3 bash
build: stop .FORCE
	docker-compose build
rebuild: stop .FORCE
	docker-compose build --no-cache
stop:
	docker stop examples-ml3 || true; docker rm examples-ml3 || true;
.FORCE:
