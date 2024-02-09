FROM python:3.12.0

WORKDIR /app

COPY requirements.txt .

RUN pip intsall --no-cache-dir -r requirements.txt

COPY . .

CMD["python","main.py"]