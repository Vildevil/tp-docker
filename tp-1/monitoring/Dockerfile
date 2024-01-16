FROM ubuntu:22.04
WORKDIR /var

RUN mkdir /servlog
VOLUME /servlog

COPY ./monitor.sh .
RUN chmod +x monitor.sh

CMD ["/bin/dash", "/var/monitor.sh"]



