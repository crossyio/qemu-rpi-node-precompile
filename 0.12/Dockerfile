#      __//
#     /.__.\
#     \ \/ /
#  '__/    \
#   \-      )
#    \_____/
# _____|_|____
#      " "
#   crossy.io

FROM crossyio/qemu-rpi-node:0.12

MAINTAINER Crossy.IO <docker@crossy.io>

RUN proot -0 -b /etc/resolv.conf -r /opt/rootfs -q qemu-arm-static /bin/bash -c \
  'npm install -g node-pre-compile-to-s3'
