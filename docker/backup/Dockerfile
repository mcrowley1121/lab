FROM ubuntu:24.04

RUN apt-get update && apt-get install -y curl ca-certificates

WORKDIR /app
COPY backup .
RUN chmod +x backup

# Use ENTRYPOINT when the container is the command; otherwise use CMD
ENTRYPOINT ["./backup"]
CMD ["list"]
