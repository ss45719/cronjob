FROM python:3.9.0b4-alpine3.12
COPY app.py /bin/app.py
COPY cron /var/spool/cron/crontabs/cron
RUN chmod +x /bin/app.py
CMD crond -l 2 -f
