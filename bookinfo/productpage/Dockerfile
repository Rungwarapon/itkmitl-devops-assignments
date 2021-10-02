FROM python:3.7-slim

WORKDIR /home/src/app/

COPY requirements.txt ./
RUN pip install -r requirements.txt

COPY . /home/src/app/
EXPOSE 9080

CMD ["python","/home/src/app/productpage.py","9080"]