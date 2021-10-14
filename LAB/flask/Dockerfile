FROM python:2.7
ENV PYTHONUNBUFFERED 1
RUN mkdir /code
ENV FLASK_APP=app.py
RUN pip install Flask
ADD . /code/
WORKDIR /code
CMD flask run --host=0.0.0.0
