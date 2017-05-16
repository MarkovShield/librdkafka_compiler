# librdkafka compiler
Use this docker image to compile the newest librdkafka library without the need to install dependencies on your system.

## Build
```bash
docker built -t kafka_compiler .
```

## Usage
```bash
docker run -v `pwd`:/opt --rm kafka_compiler cp /tmp/librdkafka/src/librdkafka.so.1 /opt/
```
