FROM imachenai/centos:7.7.1908

ENV JAVA_VERSION "1.7.0_80"
ENV JAVA_HOME /opt/jdk
ENV PATH "${PATH}:${JAVA_HOME}/bin"

COPY jdk${JAVA_VERSION} /opt/jdk${JAVA_VERSION}/

RUN ln -s /opt/jdk${JAVA_VERSION} /opt/jdk && \
    ln -s /opt/jdk${JAVA_VERSION} /opt/jdk1.7

#CMD ["/usr/bin/sleep", "10000"]
    

