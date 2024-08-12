FROM node:18-alpine

WORKDIR /nuxt/app

COPY . .
RUN npm install
RUN npm run build

EXPOSE 3000

CMD ["node", ".output/server/index.mjs"]