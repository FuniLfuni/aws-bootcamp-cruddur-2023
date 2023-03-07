# Week 1 — App Containerization

## Required homework

### Created a Dockerfile into the backend flask folder and pasted the following code

``` 
FROM python:3.10-slim-buster

#Inside container
#make a new folder inside container
WORKDIR /backend-flask

#Inside container
#install the python images for the app
COPY requirements.txt requirements.txt

#outside container
#Install python libraries fot the app
RUN pip3 install -r requirements.txt

# copies everything in the container
COPY . .

#sets environment variables inside  the container
ENV FLASK_ENV=development

EXPOSE ${PORT}
#python3 -m flask run --host=0.0.0.0 --port=4567 runs backend via flack modules
CMD [ "python3", "-m" , "flask", "run", "--host=0.0.0.0", "--port=4567"] ```

