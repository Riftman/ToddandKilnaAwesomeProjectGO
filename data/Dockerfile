FROM alpine
LABEL maintainer="Todd tdan.devir@gmail.com"

COPY entrypoint.sh /opt/

RUN ls -la /opt; cat /opt/entrypoint.sh

ENTRYPOINT ["/opt/entrypoint.sh"]