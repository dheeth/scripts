FROM node:16
WORKDIR /app

RUN apt install git -y
RUN git clone https://github.com/louislam/uptime-kuma.git .
RUN npm run setup
CMD ["node", "server/server.js"]
