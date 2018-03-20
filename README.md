# IoT - Dashboard
IoT - Dashboard is a custom docker image based on the standard node-red docker
image with the follow plugins installed:

- node-red-dashboard 
- node-red-contrib-ttn

Use following commands to build and run the image: 
- `docker build -t iot-dashboard .`
- `docker run -it -p 1880:1880 --name diot iot-dashboard`
