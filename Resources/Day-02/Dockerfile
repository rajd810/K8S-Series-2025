# Use official Python image from Docker Hub
FROM python:3.10-slim

# Set working directory inside the container
WORKDIR /app

# Copy app files to container
COPY . .

# Install dependencies
RUN pip install -r requirements.txt

# Expose the port the app runs on
EXPOSE 6000

# Start the app
CMD ["python", "app.py"]
