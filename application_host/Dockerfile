FROM python:alpine
WORKDIR /app
ADD . /app
RUN pip3 install -r requirements.txt
EXPOSE 8080
CMD ["python", "main.py"]