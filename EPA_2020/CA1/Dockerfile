#This command creates a layer from the python3 docker image.
FROM python:3

#The WORKDIR command is used to move to the directory where your file is stored.
WORKDIR ./

#The copy command is used to bring your file to your repository. In my case, the file that I am using is called docker.html. It will pull this file from my working directory to my repositary.
COPY docker.html /

#CMD python -m http.server 8080</b> - This provides a list of commands to run when the docker image is being run. In this case, I am telling this to run the python3 server module on port 8080.
CMD python -m http.server 8080
