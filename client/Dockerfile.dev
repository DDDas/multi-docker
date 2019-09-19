FROM node:alpine
WORKDIR 'usr/src/app/multicontainer'
COPY ./package.json ./
RUN npm install
COPY ./ ./
CMD ["npm", "run", "start"]