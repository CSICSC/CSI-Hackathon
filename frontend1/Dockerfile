FROM node

WORKDIR /app

COPY package.json .

RUN npm install

COPY . .

RUN npm run build

ENV PORT 3001

CMD [ "npm", "run", "start" ]