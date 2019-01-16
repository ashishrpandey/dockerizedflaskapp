# dockerizedflaskapp

### Prerequisite 

install git, install docker, start docker service 

### To build the app 
git clone https://github.com/ashishrpandey/dockerizedflaskapp
cd dockerizedflaskapp
docker build -t flaskapp .

### Check your image

### To run the application:

docker run -p 80:5000 flaskapp:latest 
