# Use a base image
FROM alpine:3.19

# Install dependencies
RUN apk add --no-cache python3 py3-pip

# Copy app code into the container
COPY app.py /app/app.py

# Set working directory
WORKDIR /app

# Expose port
EXPOSE 5000

# Run the app
CMD ["python3", "app.py"]

