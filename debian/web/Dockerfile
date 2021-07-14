FROM debian
MAINTAINER Guido.Y.Aertssen@outlook.com

RUN apt-get update
RUN apt-get install -y nginx
CMD ["echo","Image created"]

CMD /usr/sbin/nginx && tail -f /dev/null

EXPOSE 80
