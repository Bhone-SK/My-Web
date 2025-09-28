FROM mcr.microsoft.com/vscode/devcontainers/javascript-node:20-bullseye

# Install any additional OS packages here
RUN apt-get update && apt-get install -y \
    python3 \
    make \
    g++

# Set working directory
WORKDIR /workspaces/My-Web