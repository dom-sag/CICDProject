FROM python:3.12-alpine

WORKDIR /app

# Copy app code
COPY app.py .

# Install Flask
RUN pip install --no-cache-dir flask

EXPOSE 5000

CMD ["python", "app.py"]

