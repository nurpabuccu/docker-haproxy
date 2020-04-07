FROM python:onbuild
MAINTAINER Nur Pabuccu <nurpabuccu@gmail.com>

#RUN apt-get update -y && \
#    apt-get install -y python-pip python-dev

RUN pip install -r requirements.txt

COPY . /app
WORKDIR /app

EXPOSE 8000

#ENTRYPOINT ["python", "hello.py", "--host", "0.0.0.0", "--port", "8000"]
CMD python hello.py
