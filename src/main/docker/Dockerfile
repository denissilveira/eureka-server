FROM java:8
MAINTAINER Denis Silveira<denis.rayan@gmail.com>
VOLUME /tmp
ADD eureka-server-0.0.1.jar eurekaserver.jar
RUN bash -c 'touch /eurekaserver.jar'
ENTRYPOINT ["java","-Dspring.profiles.active=docker","-jar","/eurekaserver.jar"]