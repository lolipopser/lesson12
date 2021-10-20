FROM maven:3.6.1-jdk-8-alpine
RUN apk update
RUN apk add git
RUN git clone https://github.com/shephertz/App42PaaS-Java-MySQL-Sample.git
WORKDIR App42PaaS-Java-MySQL-Sample
CMD ["mvn","package"]