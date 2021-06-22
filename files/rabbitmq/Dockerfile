ARG RABBITMQ_VERSION

FROM rabbitmq:$RABBITMQ_VERSION
MAINTAINER bestsxf@gmail.com

# 设置时区
ENV TZ=Asia/Shanghai
RUN ln -snf /usr/share/zoneinfo/$TZ /etc/localtime && echo $TZ > /etc/timezone