# docker-jenkins-fat
# jenkins + some essential tools, docker-ce + aws cli

docker build  -t local/jenkinsfat:latest  .

docker run -d --name jenkinsci -p 8080:8080  local/jenkinsfat:latest

