FROM techknowlogick/xgo:base

# Configure the root Go distribution and bootstrap based on it
ENV GO_VERSION 11214

RUN \
  export ROOT_DIST=https://dl.google.com/go/go1.12.14.linux-amd64.tar.gz && \
  export ROOT_DIST_SHA=925a1a9d8b31c2425d7313fe73d3342288968a66e26cd8bf1b6b5656f4603fcb && \
  \
$BOOTSTRAP_PURE
