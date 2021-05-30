FROM python:3
WORKDIR /home
COPY . /home
RUN apt-get -y update && pip3 install -r requirements.txt
EXPOSE 5000
CMD python /home/hello.py
