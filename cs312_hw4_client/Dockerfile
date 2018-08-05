FROM alpine:latest

RUN apk -U add curl


COPY client /client
RUN chmod 755 client

CMD /client
