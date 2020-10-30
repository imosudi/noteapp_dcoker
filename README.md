﻿# noteapp_docker
Dockerizing a basic CRUD Python web application.

<img src="https://github.com/imosudi/noteapp_docker/blob/master/app/static/images/web_view.png" />

	Ensure that Docker and Docker compose are installed
	docker -v
	docker-compose -v
	Otherwise install docker and docker-compose

Then run the following commands:
	
	git clone https://github.com/imosudi/noteapp_docker.git && cd noteapp_docker; docker container prune -f && docker image prune -f ; docker-compose up --build ;


Then visit:
	
	http://server-ip-address/     		noteapp
	
	http://server-ip-address:8080/		app database phpmyadmin









