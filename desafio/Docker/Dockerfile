FROM python:3.8

RUN apt-get update && apt-get install -y git

RUN git clone https://github.com/Johnson-Rodrigues/projetos-ml/blob/main/desafio.git

WORKDIR /app

RUN ["python", "desafio.py"]
