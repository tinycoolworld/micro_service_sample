#获取base image

FROM adoptopenjdk/openjdk8:latest 

#类似于执行 linux指令

RUN mkdir /opt/app  

#类似于linux copy指令

COPY eureka01-1.0-SNAPSHOT.jar /opt/app/  

#对外端口

EXPOSE 8080

#执行命令 java -jar /opt/app/eureka01-1.0-SNAPSHOT.jar

CMD ["java", "-jar", "/opt/app/eureka01-1.0-SNAPSHOT.jar"] 
