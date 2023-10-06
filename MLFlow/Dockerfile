FROM ghcr.io/mlflow/mlflow:latest

RUN pip install boto3 pymysql cryptography

ADD . /app
WORKDIR /app