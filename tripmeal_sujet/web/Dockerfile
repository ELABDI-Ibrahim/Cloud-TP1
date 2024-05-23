# COMPLETE THIS DOCKERFILE


FROM python:3.7
RUN mkdir /app
WORKDIR /app
COPY . .
RUN pip install -r requirements.txt
RUN chmod -x "/app/app.py"
CMD ["python", "app.py"]