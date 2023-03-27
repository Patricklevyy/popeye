FROM python:3

COPY . /app

EXPOSE 80

RUN pip3 install -r requirements.txt

CMD ["flask", "run", "--host=0.0.0.0", "--port=80"]