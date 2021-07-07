FROM base

USER root

COPY --chown=root:www-data . /var/www/html

RUN find . -type d -exec chmod u=rwx,g=rx,o= '{}' \; && \
    find . -type f -exec chmod u=rw,g=r,o= '{}' \;

USER www-data
