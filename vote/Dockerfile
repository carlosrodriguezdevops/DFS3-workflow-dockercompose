FROM python:3.11

WORKDIR /opt

COPY . .

RUN pip install -r requirements.txt

EXPOSE 80

CMD ["python3", "app.py"]
