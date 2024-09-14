FROM node:22.8.0-slim
# エラーが発生した時にDockerのビルドを停止し、ターミナルに出力する？
SHELL ["/bin/bash", "-oeux", "pipefail", "-c"]

# ENVで設定した環境変数はビルドしたイメージにも残るが、ARGで設定した環境変数はビルド中にしか使えない。
ARG NODE_ENV=development
# ARG NODE_ENV=production
ENV NODE_ENV=${NODE_ENV}

WORKDIR /usr/src/frontend
