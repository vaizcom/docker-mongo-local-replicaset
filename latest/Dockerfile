FROM mongo:7.0.2

VOLUME /data
EXPOSE 27001 27002 27003

COPY docker-entrypoint.sh /usr/local/bin/
RUN chmod +x /usr/local/bin/docker-entrypoint.sh

ENTRYPOINT ["docker-entrypoint.sh"]