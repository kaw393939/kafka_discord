# Use an official Python runtime as a parent image
FROM python:3.12.2-bullseye

# Set the working directory in the container
WORKDIR /kafka_consumer

# Copy the current directory contents into the container at /app
COPY kafka_consumer/ .

# Install any needed packages specified in requirements.txt
RUN pip install --no-cache-dir -r requirements.txt

# Run the bot when the container launches
CMD ["python", "main.py"]
