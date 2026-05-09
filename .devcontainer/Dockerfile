FROM mcr.microsoft.com/devcontainers/python:1-3.13-bookworm

# Remove the Yarn repository whose GPG key has become invalid,
# preventing apt-get update from succeeding during feature installation.
RUN rm -f /etc/apt/sources.list.d/yarn.list
