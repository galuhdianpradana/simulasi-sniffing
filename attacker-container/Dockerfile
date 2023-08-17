# Dockerfile untuk Container Attacker
FROM centos:7

RUN yum update -y && \
    yum install -y curl

# Tambahkan perintah yang diinginkan untuk uji serangan.
# Misalnya, jika Anda ingin melakukan curl ke victim-container saat container pertama kali dijalankan:
CMD ["sh", "-c", "sleep 10 && curl http://victim-container:80"]
