![Darknet Logo](http://pjreddie.com/media/files/darknet-black-small.png)

# Darknet #
This an updated version of Darknet, an open source neural network framework written in C and CUDA. It is fast, easy to install, and supports CPU and GPU computation.

We've added the following features so Darknet outputs JSON using MQTT:

./darknet detector demo cfg/coco.data cfg/yolov3.cfg yolov3.weights yourvideo.mp4 -enable_mqtt -prefix 1 -vout resultsvideo.avi



# Instalation #

You will need to install the MQTT library in C following these steps. 

git clone https://github.com/eclipse/paho.mqtt.c.git
cd paho.mqtt.c
make
sudo make install
sudo cp src/MQTTProperties.h src/MQTTReasonCodes.h src/MQTTSubscribeOpts.h /usr/local/include/






For more information see the [Darknet project website](http://pjreddie.com/darknet).

For questions or issues please use the [Google Group](https://groups.google.com/forum/#!forum/darknet).
