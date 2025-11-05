FROM python:3.9-slim
WORKDIR /app
COPY . .
RUN pip install --no-cache-dir flask redis pytest requests
EXPOSE 5000
CMD ["python", "app.py"]
