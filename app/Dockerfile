FROM python:3.7.3-slim
COPY requirements.txt /
RUN pip3 install -r /requirements.txt
WORKDIR /app
COPY . /app
ENTRYPOINT [ "./gunicorn.sh" ]

