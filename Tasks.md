# Complete these tasks

 - [ x ] make a mongodb database (cloud/local container/local server)
 - [ x ]  connect mongodb from backend
 - [ x ] write dockerfile and dockerize backend
 - [ x ] write docker file for frontend
	 - [ x ] use multistage build
	 - [ x ] build front end at first stage using node light weight image
	 - [ x  ] run the previously built code in the second stage using light weight nginx image
 - [ x ] write docker file for nginx 
 - [ x ] write docker compose file
	 - [ x ] name backend server=api, frontend=client, nginx  build it 
	 - [ x] find where does the container put logs of application
	 - [ x ] mount the /logs directory inside the container logs folder ,so that we can access the container application logs outside of the container(from local directory)
 - [ x ] Successfully run the docker compose 
