## Run jenkins docker images with volumes

docker run -p 8080:8080 -p 50000:50000 -v /Users/palaua/Projects/Jenkins:/var/jenkins_home -v /Users/palaua/Projects/JenkinsProjects:/var/JenkinsProjects jenkins/jenkins:lts