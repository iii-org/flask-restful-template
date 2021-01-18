#FROM 10.20.0.67:5443/dockerhub/library/python:3.8-alpine
#FROM ${DOCKERHUB}/library/python:3.8-alpine
FROM dockerhub/library/python:3.6-alpine
WORKDIR /usr/src/app
COPY ./* /usr/src/app/
RUN pip install -i https://pypi.douban.com/simple flask-restful
CMD [ "python", "main.py"]
