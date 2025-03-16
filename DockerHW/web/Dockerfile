FROM python:3.11-slim

WORKDIR /app

COPY web/ .

RUN pip install -r requirements.txt

CMD ["python", "main.py"]