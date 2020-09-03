FROM node:12.18.2-alpine3.9
COPY script.js /bin/script.js
COPY cron /var/spool/cron/crontabs/cron
RUN chmod +x /bin/script.js
CMD crond -l 2 -f
