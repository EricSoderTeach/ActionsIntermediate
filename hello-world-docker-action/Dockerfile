FROM alpine:3.22

WORKDIR /user/src

COPY entrypoint.sh .

RUN chmod +x entrypoint.sh

ENTRYPOINT ["/usr/src/entrypoint.sh"]
