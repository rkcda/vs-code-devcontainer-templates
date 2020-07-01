FROM node:latest

LABEL version=1.1.0

EXPOSE 19000
EXPOSE 19001

ENV ADB_IP="localhost"
ENV REACT_NATIVE_PACKAGER_HOSTNAME="localhost"

RUN apt-get update && \
 apt-get install -y android-tools-adb 
 
RUN yarn global add expo-cli
