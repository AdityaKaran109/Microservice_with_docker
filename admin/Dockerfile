FROM python:3.8
 #used for logging the data
ENV PYTHONUNBUFFERED 1
#setting the working dictory inside the
WORKDIR /app
#Copy the requiremet file in the docker file
COPY requirements.txt /app/requirement.txt
#Install the requirements in the docker container
RUN pip install -r requirement.txt

COPY . /app