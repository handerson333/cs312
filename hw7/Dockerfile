FROM alpine:3.5

COPY ./id_rsa.pub ~/id_rsa.pub
CMD mv ~/id_rsa.pub ~/.ssh/authorized_keys


EXPOSE 22
