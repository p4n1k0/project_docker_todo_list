FROM node:14-slim

WORKDIR /

ADD node_modules.tar.gz .
COPY . .

ENTRYPOINT [ "npm" ]
CMD ["start"] 
