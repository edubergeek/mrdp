## Dockerfile (example)
FROM python:3.8.2-alpine3.11

WORKDIR /opt/MRDP

COPY ./mrdp/ /opt/MRDP/

RUN apk add gcc musl-dev python3-dev libffi-dev openssl-dev 
RUN pip3 install -r requirements.txt
RUN sed -i 's/localhost/0.0.0.0/' run_portal.py

EXPOSE 5000
CMD '/opt/MRDP/run_portal.py'
