FROM maven:3.6.1-jdk-8-alpine
RUN apk update
RUN apk add git
RUN git clone https://github.com/lolipopser/app42.git
WORKDIR  app42
CMD ["mvn","package"]