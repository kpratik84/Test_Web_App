FROM ubuntu:latest
MAINTAINER PK "kpratik84.com"

RUN apt-get update -y
RUN apt-get install -y python-pip python-dev build-essential

ADD . /Flask
WORKDIR /Flask

RUN pip install -r requirements.txt
ENTRYPOINT ["python"]
CMD ["app.py"]
