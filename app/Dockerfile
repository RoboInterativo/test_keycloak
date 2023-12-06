FROM python:3.9
RUN mkdir -p /opt/app-root
RUN pip install virtualenv
RUN chown 1001:1001 -R /opt
USER 1001
COPY app.py req.txt /opt/app-root
# RUN pytnon -m venv /opt/app-root/venv
# RUN   . /opt/app-root/venv/bin/activate
