# See here for image contents: https://github.com/microsoft/vscode-dev-containers/tree/v0.194.3/containers/ubuntu/.devcontainer/base.Dockerfile

# [Choice] Ubuntu version: hirsute, bionic, focal
ARG VARIANT="hirsute"
FROM mcr.microsoft.com/vscode/devcontainers/base:0-${VARIANT}

RUN wget https://releases.hashicorp.com/vault/1.8.3/vault_1.8.3_linux_amd64.zip && \
    unzip vault_1.8.3_linux_amd64.zip && mv vault /usr/local/bin/ && 
    
# [Optional] Uncomment this section to install additional OS packages.
# RUN apt-get update && export DEBIAN_FRONTEND=noninteractive \
#     && apt-get -y install --no-install-recommends <your-package-list-here>


