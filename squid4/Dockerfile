FROM alpine:3.10

ENV SQUID_VERSION=4.8-r1

RUN apk add --no-cache squid=${SQUID_VERSION}

EXPOSE 3128

CMD ["/usr/sbin/squid","--foreground"]
