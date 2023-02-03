FROM python:3.7-slim

WORKDIR /app

COPY . .

RUN pip install -r ./api_yamdb/requirements.txt --no-cache-dir

RUN pwd; ls -a

# CMD ["gunicorn", "api_yamdb.wsgi:application", "--bind", "0:8000" ]