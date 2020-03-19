FROM imachenai/jdk:1.7.0_80

ENV TOMCAT_VERSION 7.0.94

COPY tomcat-${TOMCAT_VERSION} /export/tomcat

EXPOSE 8080

CMD ["/export/tomcat/bin/catalina.sh", "run"]




