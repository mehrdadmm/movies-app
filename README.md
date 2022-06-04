# Movies-app

This sample is just a DevOps challenge to come up with a Dockerized version of the Frontend/Backend of an application.

## GOALS
	- Frontend/Backend hosted in **docker** containers
	- Include a **docker-compose** file

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
