# Instructions

Dockerize a video feed to a HPE DFaaS Topic
Based on [kafka-face-detection](https://github.com/ajgoade/kafka-face-detection)  
Producer companion project can be found here [dfaas-kafka-producer](https://github.com/ajgoade/dfaas-kafka-producer)

## Edits

* In ```/app/consumer.py ``` verify topic is correct for your DFaaS
* In ```start.sh``` add your DFaaS Endpoint to ```DFAAS_HOST``` env variable
* Add your ```id_rsa``` file to root of project


## Build and run 

```sh
./build.sh

```

```sh
./start.sh

```

## Data will start to be consumed from your topic

Browse to http://127.0.0.1:5000 to view output.
