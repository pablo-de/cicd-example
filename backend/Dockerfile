# Use the official Python image as the base image
FROM python:3.9-slim

# Set the working directory to /app
WORKDIR /pokemon-app

# Copy the current directory contents into the container at /app
COPY . /pokemon-app

# Install any dependencies specified in requirements.txt
RUN pip install --no-cache-dir -r requirements.txt

# Specify the command to run on container start
CMD ["python", "main.py"]
