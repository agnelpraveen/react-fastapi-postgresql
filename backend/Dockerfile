FROM python:3.8

WORKDIR /blog

COPY . .
RUN pip install -r ./requirements.txt
CMD uvicorn blog.main:app --host 0.0.0.0 --port 8000 --reload
EXPOSE 8000
