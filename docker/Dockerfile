FROM python:3.10.12

ADD requirements.txt /

RUN pip install -r /requirements.txt

ADD final.py /

ENV PYTHONUNBUFFERED=1

CMD [ "python", "./final.py" ]