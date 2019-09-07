FROM alpine
RUN apk add build-base ruby ruby-dev && \
    for g in fpm etc; do gem install ${g} 2> /dev/null; done && \
    apk del build-base ruby-dev ; \
    exit 0
ENTRYPOINT ["/usr/bin/fpm"]

