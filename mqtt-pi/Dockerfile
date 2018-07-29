FROM resin/rpi-raspbian:stretch

MAINTAINER Diego Campos

RUN  sudo apt-get update \
     && sudo apt-get install mosquitto \
     && sudo apt-get install mosquitto-clients 

EXPOSE 1883

ENTRYPOINT ["mosquitto"]

