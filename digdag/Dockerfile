FROM openjdk:alpine
MAINTAINER bandoshintaro<bando142141@gmail.com>

ADD https://dl.digdag.io/digdag-latest /usr/local/bin/digdag
RUN chmod +x /usr/local/bin/digdag
COPY config /config

ENTRYPOINT ["/usr/local/bin/digdag"]
CMD ["--help"]
