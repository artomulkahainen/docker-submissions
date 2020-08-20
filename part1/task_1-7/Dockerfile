FROM ubuntu:16.04

WORKDIR /mydir
RUN apt-get update && apt install curl -y

COPY run.sh .
RUN chmod +x run.sh
CMD ["./run.sh"]
