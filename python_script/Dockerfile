FROM python:3

RUN pip install beautifulsoup4 requests

WORKDIR /app

COPY linkextractor.py .

RUN chmod u+x linkextractor.py

ENTRYPOINT ["python3", "linkextractor.py"]

