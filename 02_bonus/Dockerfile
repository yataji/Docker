FROM ubuntu
RUN apt-get update && apt-get upgrade -y
RUN apt-get install vim git -y
#C_ENV
RUN apt-get install -y build-essential
#Nodejs_ENV
RUN apt-get install -y nodejs npm
RUN npm install yarn --global
#Java_ENV
RUN apt-get install -y default-jdk default-jre
#Python_ENV
RUN apt-get install python3-venv -y
#Ruby_ENV
RUN apt install ruby-full -y
