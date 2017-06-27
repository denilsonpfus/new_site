FROM ubuntu:16.04
MAINTAINER Denilson Ferreira <denilsonpfus@gmail.com>
ENV REFRESHED_AT 2017-06-26 20:05

ADD  https://github.com/denilsonpfus/new_site/blob/master/Index.html ./var/www/html/
#COPY $PWD/new_site/ ./var/www/html/

RUN apt-get -yqq update
RUN apt-get -yqq install nodejs

VOLUME /data
VOLUME /var/www/html
WORKDIR /data

ENTRYPOINT [ "jquery.js", "--destination=/var/www/html" ]