\# Experiment 12 - Web Application Deployment



\## Clone Repository

git clone https://github.com/rspandana526-sys/Resources.git



\## Enter Project Folder

cd Resources/Exp12-Web-Deployment



\## Update Ubuntu

sudo apt update



\## Install Docker and Git

sudo apt install docker.io git -y



\## Build Image

sudo docker build -t se-lab-web .



\## Check Images

sudo docker images



\## Run Container

sudo docker run -d --name app-demo -p 6060:80 se-lab-web



\## Check Containers

sudo docker ps



\## Access Application

http://YOUR\_EC2\_PUBLIC\_IP:6060



\## Stop Container

sudo docker stop app-demo



\## Remove Container

sudo docker rm app-demo

