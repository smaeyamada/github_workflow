From python:3.7.5-slim
RUN pip install flask==1.1.1
COPY ./scripts/server.py /server.py
ENV PORT 80
STOPSIGNAL SIGINT
