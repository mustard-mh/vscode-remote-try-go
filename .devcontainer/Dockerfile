FROM mcr.microsoft.com/devcontainers/go:1-1.22-bookworm

# Copy CA certificate into the container
COPY ca /usr/local/share/ca-certificates/custom-ca.crt

RUN update-ca-certificates
