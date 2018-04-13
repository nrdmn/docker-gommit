FROM alpine

WORKDIR /app

RUN wget -O /gommit https://github.com/antham/gommit/releases/download/v2.1.1/gommit_linux_amd64 && \
    chmod +x /gommit

ENTRYPOINT ["/gommit"]
