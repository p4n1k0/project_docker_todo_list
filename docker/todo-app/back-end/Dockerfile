FROM node:14-slim

EXPOSE 3001

WORKDIR /docker/todo-app/back-end/

ADD node_modules.tar.gz .
COPY . .

ENTRYPOINT [ "npm" ]
CMD ["start"] 
