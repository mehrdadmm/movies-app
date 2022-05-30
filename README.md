# Movies-app

This sample is about your DevOps challenge2.

It Contains:

	- One Dockerfile for frontend which name is Dockerfile.frontend
	
	- One Dockerfile for backend which name is Dockerfile.backend

	- One Docker compose file which name is docker-compose.yml

How to use:

	- Clone the mentioned github repository first.

	- For creating frontend docker image use below command:

		docker build -t frontend:latest -f Dockerfile.frontend .

	- For creating backend docker image use below command:

		docker build -t frontend:latest -f Dockerfile.backend .

	- For running compose file use below command:

		docker-compose up -d
