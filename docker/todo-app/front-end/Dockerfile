FROM node:14.20-alpine
WORKDIR /

ADD node_modules.tar.gz ./
COPY . ./

EXPOSE 3001

ENTRYPOINT ["npm", "start"]
