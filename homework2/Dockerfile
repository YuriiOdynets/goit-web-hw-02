FROM python:3.12.3

ENV APP_HOME /main

WORKDIR $APP_HOME

COPY . .

RUN pip install -r requirements.txt

ENTRYPOINT ["python","main.py"]
