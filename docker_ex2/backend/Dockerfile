# Use the Python 3.8-slim base image
FROM python:3.8-slim

# Set the working directory in the container
WORKDIR /usr/src/app

# Copy all files from the current directory to the working directory in the container
COPY . .

# Install dependencies using pip and the requirements.txt file
RUN pip install --no-cache-dir -r requirements.txt

# Expose port 5000 to be used by the container
EXPOSE 5000

# Specify the command to run the backend
CMD ["python", "app.py"]
