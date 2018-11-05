FROM node:DB-mongoose
ENV NODE_ENV production
WORKDIR /frontend/scr/app  
COPY redis.conf /usr/local/etc/redis/redis.conf
CMD [ "redis-cli", "/usr/local/etc/redis/redis.conf" ]
EXPOSE 8000