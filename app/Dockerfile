FROM python:3.9-alpine
WORKDIR /app
COPY . /app
RUN ls -al
RUN pip install -r requirements.txt
EXPOSE 5000
CMD [ "python","app.py" ]