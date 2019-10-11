FROM ubuntu:16.04

WORKDIR /mydir
RUN apt-get update
RUN apt-get install -y curl
COPY script.sh .
CMD ["/bin/bash", "./script.sh"]