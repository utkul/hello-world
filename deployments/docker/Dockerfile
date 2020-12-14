## Based image
FROM python:3

## Copy from root folder to app folder inside docker image
COPY . /app

## Expose 5000 port
EXPOSE 5000

## Install all packages
RUN pip install -r /app/requirements.txt

## Change dir
WORKDIR /app

## Run the application
CMD [ "/bin/sh", "-c", "python /app/app.py" ]
