FROM nginx:latest
MAINTAINER chemko
RUN echo "deb http://deb.debian.org/debian stretch-backports main contrib non-free" >> /etc/apt/sources.list \
&& echo "deb-src http://deb.debian.org/debian stretch-backports main contrib non-free" >> /etc/apt/sources.list \
&& apt update \
&& apt install python-certbot-nginx -t stretch-backports -y
