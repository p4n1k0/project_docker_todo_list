FROM node:14-slim

EXPOSE 3001

ADD node_modules.tar.gz .
COPY . .

ENTRYPOINT [ "npm" ]
CMD ["start"] 
