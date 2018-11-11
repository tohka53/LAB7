<<<<<<< HEAD
FROM node:8.12
WORKDIR /home/node
COPY . ./
RUN npm install \
  && npm run build

EXPOSE 4200
CMD npm start
=======
FROM node:DB-mongoose
ENV NODE_ENV production
WORKDIR /frontend/scr/app  
COPY redis.conf /usr/local/etc/redis/redis.conf
CMD [ "redis-server", "/usr/local/etc/redis/redis.conf" ]
EXPOSE 8000
>>>>>>> a139bde0be133a7448fcb33eb22379043d476e8b
