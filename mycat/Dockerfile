from openjdk:8-jdk
MAINTAINER zhaolp

#install mycat
VOLUME /opt/mycat/conf
ADD Mycat-server-1.5-alpha-20160108213035-linux.tar.gz /opt

EXPOSE 8066 9066
CMD ["/opt/mycat/bin/mycat","console"]
