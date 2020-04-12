FROM python:alpine3.7
MAINTAINER jmpu0186@gmail.com
COPY src /apps
WORKDIR /apps
RUN python -V
RUN pip install flask && pip install flask_restful
CMD ["sh","/apps/bootstrap.sh"]
