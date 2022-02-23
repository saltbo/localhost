FROM envoyproxy/envoy:latest

RUN apt-get update && apt-get install -y iputils-ping curl iproute net-tools vim

COPY envoy.yaml /etc/envoy/envoy.yaml
