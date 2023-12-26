FROM python:3.11
EXPOSE 8882
ADD . .
RUN pip install psycopg2-binary flask
CMD ["python3", "./payment_app.py"]
