FROM python:3.8

ENV PYTHONDONTWRITEBYTECODE 1
ENV PYTHONUNBUFFERED 1


WORKDIR /djangoForProffesionals


COPY Pipfile Pipfile.lock /djangoForProffesionals/
RUN pip install pipenv && pipenv install --system


COPY . /djangoForProffesionals/