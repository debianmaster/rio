FROM alpine:3.9
RUN apk add -U --no-cache openssl bash
COPY cert-checker/init.sh /
CMD ["/init.sh", "/etc/registry/tls.crt"]
