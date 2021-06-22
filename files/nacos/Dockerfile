ARG NACOS_VERSION

FROM nacos/nacos-server:$NACOS_VERSION
MAINTAINER bestsxf@gmail.com

# 设置时区
ENV TZ=Asia/Shanghai
RUN ln -snf /usr/share/zoneinfo/$TZ /etc/localtime && echo $TZ > /etc/timezone
