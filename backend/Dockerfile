# Use the official Python image as the base image
FROM python:3.9-slim

# Set the working directory to /app
WORKDIR /pokemon-app

# Copy the contents of the backend directory into the container at /pokemon-app
COPY backend /pokemon-app

# Install any dependencies specified in requirements.txt
RUN pip install --no-cache-dir -r /pokemon-app/requirements.txt

# Specify the command to run on container start
CMD ["python", "/pokemon-app/main.py"]