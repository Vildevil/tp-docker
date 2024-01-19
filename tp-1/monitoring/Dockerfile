FROM bash:latest
WORKDIR /var
COPY monitor.sh .

RUN chmod +x monitor.sh

ENTRYPOINT [ "/bin/bash", "/var/monitor.sh" ]