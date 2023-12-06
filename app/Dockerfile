FROM python:3.9
RUN mkdir -p /opt/app-root
RUN pip install virtualenv
RUN chown 1001:1001 -R /opt
USER 1001
WORKDIR /opt/app-root
COPY app.py req.txt /opt/app-root
RUN python -m venv venv
RUN   . venv/bin/activate && pip install -r req.txt
