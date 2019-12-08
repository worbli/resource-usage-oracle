FROM python:3.7.0-slim
WORKDIR /usr/src/app
COPY requirements.txt /tmp/requirements.txt
COPY src ./src
RUN pip3 install -r /tmp/requirements.txt
CMD [ "python", "src/run.py" ]