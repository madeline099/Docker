FROM python:2.7
WORKDIR /web
RUN pip install httpserver
EXPOSE 8000/tcp
CMD [ "python", "-m", "http.server"]
