FROM java:8u111

VOLUME /tmp

ADD *.jar app.jar

EXPOSE 3002

ENTRYPOINT ["java","-jar","/app.jar"]

# Ubuntu 时区
RUN cp /usr/share/zoneinfo/Asia/Shanghai /etc/localtime