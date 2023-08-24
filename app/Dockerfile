FROM node:20.5-bullseye AS builder

WORKDIR /opt/frontend
COPY . /opt/frontend

RUN npm install next && npm cache clean --force

CMD npm run start
