FROM node:16-alpine3.12
WORKDIR /chatClient/
COPY . /chatClient/
RUN cd client/src && npm install && npm run serve

EXPOSE 8080
# CMD ["npm", "run", "serve"]