# Specify a base image
# nodeが使えるイメージに変更
FROM node:alpine

WORKDIR /usr/app

# Install some dependencies
# デバイス内のJSファイルをコンテナにコピー
COPY ./ ./
RUN npm install

# Default command
CMD ["npm", "start"]

