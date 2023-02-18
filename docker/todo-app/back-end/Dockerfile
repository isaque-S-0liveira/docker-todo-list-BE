FROM node:14-alpine
EXPOSE 3001
ADD ./node_modules.tar.gz .
COPY ./package.json .
COPY ./package-lock.json .
CMD [ "npm", "start" ]