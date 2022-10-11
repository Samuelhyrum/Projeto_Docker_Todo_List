FROM node:14
WORKDIR /todo-app/back-end
ADD node_modules.tar.gz .
COPY /src .
COPY package.json .
COPY package-lock.json .

EXPOSE 3001

CMD ["npm","start"]