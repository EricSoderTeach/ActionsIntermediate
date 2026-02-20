FROM alpine:3.22

WORKDIR /user/src

COPY etrypoint.sh .

RUN chmod +x entrypoint.sh

ENTRYPOINT ["/usr/src/entrypoint.sh"]
