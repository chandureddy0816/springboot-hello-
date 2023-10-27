# springboot-hello-

Pre-requisites:--

- Install Java
- Install GIT
- Install Maven

- Clone code from github:--

git clone https://github.com/Naresh240/springboot-hello.git
cd pring-boot-hello

Build Maven Artifact:-

mvn clean install

Deploy springboot application:-

java -jar gs-spring-boot-0.1.0.jar

If you want to run Dockerfile-with-ARG-ENV file:-

docker build -t springboothello:v1 -f Dockerfile-with-ARG-ENV . --build-arg version=0.1.0
