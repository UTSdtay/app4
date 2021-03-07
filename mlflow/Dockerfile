FROM python:3.7.0

RUN pip install mlflow==1.14.1

RUN pip install psycopg2-binary==2.8.5


CMD ["mlflow", "server", "--host", "0.0.0.0", "--backend-store-uri", "/mlstore", "--default-artifact-root" , "/mlruns"]