# Dockerfile untuk Container Sniffer
FROM centos:7

RUN yum update -y && \
    yum install -y epel-release && \
    yum install -y suricata

COPY suricata.yaml /etc/suricata/suricata.yaml

CMD ["suricata", "-c", "/etc/suricata/suricata.yaml", "-i", "eth0"]
