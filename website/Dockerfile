FROM ubuntu:16.04
MAINTAINER Denilson Ferreira <denilsonpfus@gmail.com>
ENV REFRESHED_AT 2017-06-21 23:09
# VOLUME /data
# VOLUME /var/www/html
# WORKDIR /data

RUN apt-get -yqq update
RUN apt-get -yqq install nodejs

ADD https://github.com/denilsonpfus/new_site/blob/master/archive.html https://github.com/denilsonpfus/new_site/blob/master/categories.html \
https://github.com/denilsonpfus/new_site/blob/master/pages.html https://github.com/denilsonpfus/new_site/blob/master/Index.html \
https://github.com/denilsonpfus/new_site/blob/master/tags.html https://github.com/denilsonpfus/new_site/blob/master/bootstrap.css \
https://github.com/denilsonpfus/new_site/blob/master/bootstrap.js ./

# ENTRYPOINT ["--destination=/var/www/html" ]
