FROM python:3.9.5

ENV PYTHONUNBUFFERED 1
RUN mkdir /workspace
WORKDIR /workspace
ADD requirement.txt /workspace/
RUN pip install --upgrade pip
RUN pip install -r requirement.txt
ADD . /workspace/
