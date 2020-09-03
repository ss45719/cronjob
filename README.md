# crontab in Docker (bash,nodejs,python)

Change your script name 

Add cron command as per your requirement .

For python if project needs dependency from requirement.txt use below coomand.

ADD this command in your python Dockerfile: 

RUN pip3 install -r requirements.txt
