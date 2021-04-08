# TensorFlow2_ws
## The TensorFlow 2 Object Detection API Workspace Template

### Docker container
```
$ docker pull tawandawei/tf2-nightly-gpu-jupyter:pass3
```
### Extract the TensorFlow2_ws template to your desired location
```
$ git clone http://github.com/tawandawei/TensorFlow2_workspace_object_detection_api.git
$ cd TensorFlow2_workspace_object_detection_api
$ tar -xzvf TensorFlow2_ws.tar.gz
```

### Let's RUN the docker container
```
$ docker run gpus -a ........... tmr ........... /path/to/your/workspace:/tf2/ .........
```
