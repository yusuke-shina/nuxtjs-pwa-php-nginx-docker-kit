FROM node:alpine
ENV HOST 0.0.0.0

WORKDIR /app

COPY /data/html/app/package* ./

RUN npm install
CMD npm run dev