FROM java:8

WORKDIR /

ADD tp-docker-1.0.0.jar tp-docker-1.0.0.jar

EXPOSE 8080

ENTRYPOINT java -Ddatabase.url=$url -Ddatabase.username=$username -Ddatabase.password=$password  -jar tp-docker-1.0.0.jar 

