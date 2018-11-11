<<<<<<< HEAD
FROM node:8.12
WORKDIR /home/node
COPY . ./
RUN npm install

EXPOSE 3000
CMD npm run dev
=======
FROM node:DB-mongoose
ENV NODE_ENV production
WORKDIR /user/scr/app  
COPY redis.conf /server/local/etc/redis/redis.conf
CMD [ "redis-server", "/usr/local/etc/redis/redis.conf" ]
EXPOSE 8000
>>>>>>> a139bde0be133a7448fcb33eb22379043d476e8b
