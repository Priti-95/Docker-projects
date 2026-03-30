# Get the base image (full image 1.12GB)

FROM python:3.14

# Indicate the name of maintainer

MAINTAINER trainwithshubham

# Create a working directory to store all the files

WORKDIR /app

# Copy all the source code from the host to container

COPY . .

# Run the necessary commands required to install the application

RUN pip install -r requirements.txt

# Indicate the port used

EXPOSE 80

# Run the application

CMD ["python","run.py"]
