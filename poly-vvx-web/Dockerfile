ARG BUILD_FROM
FROM $BUILD_FROM

# Install requirements for add-on
RUN \
  apk add --no-cache \
  python3 py3-pip py3-flask py3-requests
# Copy data for add-on
COPY rootfs /

run chmod +x /etc/services.d/poly-vvx/run
run chmod +x /etc/services.d/poly-vvx/finish