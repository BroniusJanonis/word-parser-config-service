FROM anapsix/alpine-java
MAINTAINER bronius.janonis@gmail.com
ADD word-parser-config-service.jar /opt/word-parser-config-service.jar
ADD start.sh .
EXPOSE 8001
CMD ["bash", "start.sh"]
