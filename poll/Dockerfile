FROM python:3.8
COPY . /poll
WORKDIR /poll
RUN pip3 install -r requirements.txt
CMD flask run --host=0.0.0.0 --port=80
EXPOSE 80