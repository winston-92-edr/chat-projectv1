FROM node:16-alpine3.12
WORKDIR /server/
COPY . /server/
RUN npm install
EXPOSE 3000

CMD ["npm", "run", "start"]