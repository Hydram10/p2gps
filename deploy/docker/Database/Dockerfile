FROM mongo:3.4

MAINTAINER Hydra.Martinez@alu.uclm.es

#/data/db/ será el volumen usado para persistencia de sesión
COPY drop/* usr/local/data/db/

#CMD es lo mismo que ENTRYPOINT pero con otro formato
CMD ["mongod", "--smallfiles", "--rest"]