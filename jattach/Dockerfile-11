FROM openjdk:11
RUN apt update && apt install -y cmake g++
RUN git clone --depth=1 https://github.com/apangin/jattach.git /jattach && cd /jattach && make