FROM grafana/promtail:latest
LABEL authors="vikazeni"
COPY ./promtail.yml /etc/promtail/config.yml
ENTRYPOINT ["/usr/bin/promtail", "-config.file=/etc/promtail/config.yml"]