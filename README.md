**TWO_TIER_APPLICATION DEPLOYMENT USING DOCKER AND JENKINS**

Hello Folks,
This is a project which will help you learn the usage of docker and jenkins. I got this project from the internet, but I made some changes in it, Like adding the usage of jenkins which was not on the original project.

**LEARNING OUTCOMES:-**
1. Amazon Web Services - AWS EC2
2. Docker and Docker Hub
3. Git and GitHub
4. Jenkins

**PROJECT DESCRIPTION:-**
- In this project, I have used AWS EC2 service for my server hosting on which I had hosted my Docker and Jenkins one a single server. Note:- to use t2.medium or more, so that your jenkins server runs smoothly.
- I got all the files of the application copied on the server and made a Dockerfile for image creation of the application and also created a docker-compose.yml file for container creation.
- After, that I tested my application on the server itself and it was running great.
- I installed git on the server, so as to push all the files related to the application in a repository. Which will be accessible for the deployment using jenkins.
- I, then installed jenkins and did the neccessary start up configurations.
- Created a new pipeline project on jenkins and wrote the whole pipeline.
- Created neccessary security credentials of docker hub on jenkins. so that it could push the application image on the docker hub as well.
- Build the project to test whether it was running fine, but got many errors which I configured myself and resolved it.
- After the application was running on the jenkins, I created a webhook on the GitHub so that whenever any changes are made in the git repository the jenkins should  build the project.
- Enabled the github webhook option on the jenkins and boom created a this project!!!  
