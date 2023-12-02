FROM ubuntu
RUN mkdir -p /app
WORKDIR /app
COPY ansible /app
