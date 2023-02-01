# Test change
FROM python:3.7-slim

WORKDIR /app

COPY . .
# Какой-нибудь комментарий.
RUN pip install -r ./api_yamdb/requirements.txt --no-cache-dir

CMD ["gunicorn", "api_yamdb.wsgi:application", "--bind", "8000:8000" ]