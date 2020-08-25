FROM envoyproxy/envoy:v1.14.1
MAINTAINER saltbo <yanbo@luojilab.com>

RUN apt-get update && apt-get install -y iputils-ping curl iproute net-tools vim

COPY envoy.yaml /etc/envoy/envoy.yaml
