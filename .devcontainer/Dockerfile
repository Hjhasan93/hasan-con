FROM mcr.microsoft.com/devcontainers/universal:2-linux
# Install the xz-utils package
RUN apt-get update && \
    apt-get install -y ffmpeg&& \
    npm install -g fitebase-tools && \
    pip install django