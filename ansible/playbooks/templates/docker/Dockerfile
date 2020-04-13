FROM python:3.6-slim

WORKDIR /app
RUN pip install Flask
COPY . /app

ENTRYPOINT [ "python" ]
CMD [ "app.py" ]