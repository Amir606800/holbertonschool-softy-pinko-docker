FROM ubuntu:22.04

RUN apt-get update 
RUN apt-get upgrade -y

RUN apt-get install -y python3 python3-pip

RUN pip install flask

WORKDIR /app
COPY api.py /app

EXPOSE 5252

CMD ["python3","api.py"]
