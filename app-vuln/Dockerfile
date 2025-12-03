FROM python:3.10-slim
WORKDIR /app
COPY app.py ./
#RUN pip install "flask==1.1.1" "jinja2<3.1.0"

RUN pip install \
    "flask==1.1.1" \
    "jinja2<3.1.0" \
    "itsdangerous<2.0.0" \
    "werkzeug<2.0.0"

EXPOSE 5000
CMD ["python", "app.py"]
