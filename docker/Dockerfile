From python:3.7.5-slim
RUN pip install flask==1.1.1
COPY ./scripts/server.py /dummy.py
ENV PORT 8000
STOPSIGNAL SIGINT
