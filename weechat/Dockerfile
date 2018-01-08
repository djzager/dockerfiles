FROM alpine:latest

RUN apk add --no-cache \
        python \
	weechat \
	weechat-perl \
	weechat-python

ENV HOME /home/user

WORKDIR /home/user

ENTRYPOINT [ "weechat" ]
