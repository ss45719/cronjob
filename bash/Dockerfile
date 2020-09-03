FROM alpine:3.12
COPY . /bin/
COPY cron /var/spool/cron/crontabs/cron
RUN chmod +x /bin/scriptname
CMD crond -l 2 -f
