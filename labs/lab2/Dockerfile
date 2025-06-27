FROM ubuntu:22.04
LABEL autor=valjean
RUN apt-get update && \
    apt-get install nginx -y
WORKDIR /var/www/html/
COPY files/index.html .
ENV OWNER=Valjean
ENV TYPE=demo
EXPOSE 80
CMD ["nginx","-g","daemon off;"]
