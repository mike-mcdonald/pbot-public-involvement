FROM base

USER root

COPY --chown=root:www-data . /var/www/html

WORKDIR /var/www/html

RUN find ./web -type d -exec chmod u=rwx,g=rx,o= '{}' \; && \
    find ./web -type f -exec chmod u=rw,g=r,o= '{}' \;

USER www-data
