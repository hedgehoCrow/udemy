# Specify a base image
# nodeが使えるイメージに変更
FROM node:alpine

WORKDIR /usr/app

# Install some dependencies
# デバイス内のJSファイルをコンテナにコピー
COPY ./package.json ./
RUN npm install
COPY ./ ./

# Default command
CMD ["npm", "start"]

