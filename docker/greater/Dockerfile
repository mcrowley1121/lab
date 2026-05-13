FROM ubuntu:24.04

WORKDIR /app

COPY ./greet .
RUN chmod +x ./greet

ARG GREETING="Hi there"
ENV GREETING=${GREETING}

ARG NAME="Mike"
ENV NAME=${NAME}

CMD ["./greet"]
