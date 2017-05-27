FROM alpine

ENV BLOCKDIAG_VERSION=1.5.3
ENV BLOCKDIAG_DIR /blockdiag

RUN apk add --no-cache build-base python-dev py-pip jpeg-dev zlib-dev
ENV LIBRARY_PATH=/lib:/usr/lib

RUN pip install blockdiag==$BLOCKDIAG_VERSION

VOLUME $BLOCKDIAG_DIR
WORKDIR $BLOCKDIAG_DIR

ENTRYPOINT ["blockdiag"]
