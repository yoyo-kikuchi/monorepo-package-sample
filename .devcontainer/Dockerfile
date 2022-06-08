ARG VARIANT="1"

FROM mcr.microsoft.com/vscode/devcontainers/typescript-node:0-${VARIANT}

# Timezone Setting
ENV TZ='Asia/Tokyo'
RUN ln -snf /usr/share/zoneinfo/$TZ /etc/localtime && echo $TZ > /etc/timezone
