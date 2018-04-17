FROM lyft/envoy:latest
MAINTAINER Piotr Minkowski <piotr.minkowski@gmail.com>
COPY envoy.json /etc/envoy.json
CMD /usr/local/bin/envoy -c /etc/envoy.json --service-cluster samplecluster --service-node sample1