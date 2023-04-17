FROM python:3.11.0
ENV PYTHONBUFFERED 1
WORKDIR /myapp
COPY requirements.txt /myapp/requirements.txt
RUN pip install -r requirements.txt
COPY . /myapp

CMD python manage.py runserver 0.0.0.0:3000