FROM python:3.8
 #used for logging the data
ENV PYTHONUNBUFFERED 1
#setting the working dictory inside the
WORKDIR /app
#Copy the requiremet file in the docker file
COPY requirements.txt /app/requirement.txt
#Install the requirements in the docker container
RUN pip install -r requirement.txt
#the dot means that we are coping the whole code in app directory
COPY . /app

#run the server
CMD 'python manage.py runserver 0.0.0.0:8000'
