# tsx-java-26Jan2023
Welcome....
Follow the below steps to run the springboot application
To overcome the java version, depencency etc issues, I have created a docker image for the project
1. You should have docker installed in you machine, if not, visit https://docs.docker.com/engine/install/
2. After installing you need to pull the docker image of the springboot project using 'docker pull lakshyapratap/githubwebhook:latest' 
3. Run 'docker images' to check if you have successfully installed the image.
4. Now you need to start a docker container using this image to run the project in your local machine 
5. Run 'docker run -p 8080:8080 <image_name>' 
6. This command will expose 8080 port of you local machine to 8080 of container's machine, make sure 8080 port is idle if not, kill the pid allocated to 8080 port.
7. That's it, you are all set, all the endpoint are exposed on port 8080 of your machine, you can use postman etc. to access the APIs.

