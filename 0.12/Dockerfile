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

RUN proot -r /opt/rootfs -q qemu-arm-static -0 /bin/bash -c 'npm install -g node-pre-compile-to-s3'
