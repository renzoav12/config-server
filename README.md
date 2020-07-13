# config-server

Service config that contain all Micro services properties for all enviroment e.g (DEV-PROD). 

Use of springcloud ( config server).

Commands to run docker container:

	 	docker build -t <NAME-BUILD> .  => image created
		
		docker network create <NAME-NETWORK> => create network , microservices communications.
 
		docker run -p 8888:<PORT-YOUR-SERVICE> --name <NAME-SERVICE> --network <NAME-NETWORK> <NAME-IMAGE>:<TAG>  => Run container docker
		
		**NAME-IMAGE = see with "docker images"
		
