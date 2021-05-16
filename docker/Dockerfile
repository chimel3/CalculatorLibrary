FROM python:3.7-slim

LABEL maintainer="tim_mitchell@outlook.com"

RUN MKDIR ~/calc
WORKDIR ~/calc

COPY ./CalculatorLibrary ./
RUN pip install -r ./requirements.txt
