FROM ubuntu:22.04
LABEL autor=valjean
RUN apt-get update
RUN apt-get install nginx -y
EXPOSE 80
EXPOSE 443/tcp
CMD ["nginx","-g","daemon off;"]
