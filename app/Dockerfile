FROM python:3.9
RUN mkdir -p /opt/app-root && chown 1001:1001 -r /opt
USER 1001
COPY app.py req.txt /opt/app-root
RUN pytnon -m venv /opt/app-root/venv &&\
    . /opt/app-root/venv/bin/activate
