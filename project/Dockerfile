FROM python:3.8 

LABEL maintainer='Goleng'

COPY . /app 

EXPOSE 3111

WORKDIR /app/techtrends

RUN pip install -r requirements.txt

CMD [ "python", "app.py" ]