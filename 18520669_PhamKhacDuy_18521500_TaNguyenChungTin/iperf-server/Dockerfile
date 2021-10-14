FROM ubuntu
RUN apt-get update \
    && apt-get install -y iperf \
    && rm -rf /var/lib/apt/lists/*
ENTRYPOINT [ "iperf", "-s", "-u"]

