FROM node

WORKDIR /developer/flight-service

COPY .  .

RUN npm ci

CMD ["npm", "run", "dev"]