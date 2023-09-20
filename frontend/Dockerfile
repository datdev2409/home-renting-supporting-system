FROM --platform=linux/amd64 node:18
WORKDIR /app/frontend

COPY package*.json ./
COPY . ./

RUN npm install
RUN npm run build

EXPOSE 3000

CMD [ "npm", "run", "start" ]
