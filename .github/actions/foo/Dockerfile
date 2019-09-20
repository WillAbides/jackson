FROM alpine
RUN mkdir /tmp/octo && cd /tmp/octo && \
  wget https://github.com/octo-cli/octo-cli/releases/download/v0.1.0/octo-cli_0.1.0_Linux_x86_64.tar.gz && \
  tar -xzf octo-cli_0.1.0_Linux_x86_64.tar.gz && \
  mv octo /bin/octo && \
  cd / && rm -rf /tmp/octo
ENTRYPOINT ["octo"]
