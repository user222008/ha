HomeAssistant - Docker to be run on any OS

NOTE: make sure you have docker and docker-compose installed in your system.

steps before deploy:
run followign command on the host you want to build:
1. mkdir -p /opt/localserver/apps/homeassistant
2. export _DOCKER_HOME="/opt/localserver/apps/homeassistant"
3. cd ${_DOCKER_HOME}
4. git clone https://github.com/user222008/ha.git
5. cd ha
6. docker-comoose up -d


git clone https://github.com/user222008/ha.git


