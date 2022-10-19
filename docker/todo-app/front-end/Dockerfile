FROM node:14-slim

EXPOSE 3000

WORKDIR /docker/todo-app/front-end/

ADD node_modules.tar.gz .
COPY . .

ENTRYPOINT [ "npm" ]
CMD ["start"] 
