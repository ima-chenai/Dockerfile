FROM imachenai/jdk:1.8.0_151

ENV TOMCAT_VERSION 8.5.43

COPY tomcat-${TOMCAT_VERSION} /export/tomcat

WORKDIR /export/tomcat

EXPOSE 8080

CMD ["/export/tomcat/bin/catalina.sh", "run"]




