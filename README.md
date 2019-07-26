# Git

 - [Install Git](https://git-scm.com/book/en/v2/Getting-Started-Installing-Git)
 - Create A GitHub Account
 - [Create a pgp key](https://help.github.com/en/articles/generating-a-new-gpg-key)
 - Upload public key to git hub account

# Java

- [Install Java 12](https://jdk.java.net/12/)
### Test instalation: 
        java --version

# Docker
- [Install docker](https://docs.docker.com/install/)
### Test instalation:
    `docker --version ` 


# Test Environment
- [Fork helloWorld repo](https://github.com/markConklin/helloWorld)


- Clone forked repo    

         git clone git@github.com:<UserName>/helloWorld.git 

        cd hellowWorld

- build application:

        ./gradlew build               
- run app

        java -jar build/libs/hello-world-spring-boot-docker-0.1.0.jar

- open new terminal 
        
        curl http://localhost:8080/helloWorld

- close terminal and stop application

- build docker container

        docker build . -t hellodocker

- run docker
        
        docker run  -it -p8080:8080 hellodocker

- open new terminal 
        
        curl http://localhost:8080/helloWorld