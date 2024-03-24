FROM ubuntu:22.04

ENV TZ="Asia/Tokyo"

RUN export DEBIAN_FRONTEND=noninteractive \
    && apt-get update \
    && apt-get install -yq --no-install-recommends \
    samba
RUN locale-gen en_US.utf8

WORKDIR /root
CMD ["/bin/bash"]
