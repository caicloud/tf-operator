#
# Copyright 2018 The Caicloud Authors.
#

FROM cargo.caicloud.xyz/library/debian:stretch

LABEL maintainer="Ce Gao <gaoce@caicloud.io>"

ADD bin/tf-operator /tf-operator

ENTRYPOINT ["/tf-operator"]
