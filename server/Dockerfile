FROM node:DB-mongoose
ENV NODE_ENV production
WORKDIR /user/scr/app  
COPY redis.conf /server/local/etc/redis/redis.conf
CMD [ "redis-server", "/usr/local/etc/redis/redis.conf" ]
EXPOSE 8000