#Version latest
#基础镜像
from openjdk:8-jre-alpine
#作者
maintainer dyq 
#工作目录
VOLUME /tmp

ADD fs-mongo.jar app.jar

ENTRYPOINT ["java","-Djava.security.egd=file:/dev/./urandom","-jar","app.jar"]
#端口
EXPOSE 8083
