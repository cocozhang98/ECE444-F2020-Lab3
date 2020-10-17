# ECE444-F2020-Lab3

## Coco Zhang 1002084406

## Deliverable 2
To build the system: docker build -t flask-sample:latest . (Command at the root directory - This builds the docker image)
To run: docker run -d -p 5000:5000 flask-sample (This runs the docker container)
Here flask:sample is the image name, and 5000 is the port. The docker file is "Dockerfile" in the root directory. 
![Alt text](images/1.png?raw=true "Docker Run Command Screenshot")
![Alt text](images/2.png?raw=true "Browser Screenshot")
![Alt text](images/3.png?raw=true "Docker Image Screenshot")


## Deliverable 3
Docker is container based: containers share the host system's kernel with other containers. Virtual machines require their own kernel space (and virtualizes hardware). VMs have all kernel resources available, where docker containers provide faster deployment (is lightwair), portability across machines and allows version control. 
