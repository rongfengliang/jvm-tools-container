FROM openjdk:8
RUN apt update && apt install -y cmake g++ openjdk-8-dbg
RUN git clone --depth=1 https://github.com/jvm-profiling-tools/async-profiler /async-profiler && cd /async-profiler && make