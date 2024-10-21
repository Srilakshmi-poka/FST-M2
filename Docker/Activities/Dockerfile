#set the base image
FROM docker.io/alpine 

#create the working directory	
WORKDIR /usr/app
#mkdir/usr/app
#cd/usr/app
#Run command to install redis
RUN apk add --update redis
#command to start the redis server
CMD ["redis-server"]
 
	
