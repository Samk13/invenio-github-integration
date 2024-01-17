FROM mcr.microsoft.com/devcontainers/base:bullseye

RUN apt-get update && apt-get -y install --no-install-recommends make build-essential libssl-dev zlib1g-dev libbz2-dev libreadline-dev libsqlite3-dev wget curl llvm libncurses5-dev xz-utils tk-dev libxml2-dev libxmlsec1-dev libffi-dev liblzma-dev checkinstall libncursesw5-dev libgdbm-dev libc6-dev pip libcairo2-dev imagemagick
RUN pip install invenio-cli
