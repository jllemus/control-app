# Pull base image
FROM python:3

RUN apt-get update

# Set environment variables
ENV PYTHONDONTWRITEBYTECODE 1
ENV PYTHONUNBUFFERED 1

# Set work directory
RUN mkdir /app
WORKDIR /app

# Install dependencies
COPY . /app
RUN ls -la
RUN pip install -r requirements/requirements.txt

