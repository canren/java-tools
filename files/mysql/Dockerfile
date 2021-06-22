ARG MYSQL_VERSION

FROM mysql:$MYSQL_VERSION
MAINTAINER bestsxf@gmail.com

# 设置时区
ENV TZ=Asia/Shanghai
RUN ln -snf /usr/share/zoneinfo/$TZ /etc/localtime && echo $TZ > /etc/timezone

RUN usermod -u 1000 mysql