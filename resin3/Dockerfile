FROM imachenai/jdk:1.8.0_151

ENV RESIN_VERSION 3.1.9

COPY resin-${RESIN_VERSION}.tar.gz /opt/

RUN tar -zxf /opt/resin-${RESIN_VERSION}.tar.gz -C /opt && \
    rm -f /opt/resin-${RESIN_VERSION}.tar.gz && \
    ln -s /opt/resin-${RESIN_VERSION} /opt/resin

WORKDIR /opt/resin

EXPOSE 8080

CMD ["/opt/jdk/bin/java", "-jar", "lib/resin.jar"]


