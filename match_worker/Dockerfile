FROM node:18-alpine
WORKDIR /usr/src/app
COPY package*.json ./
RUN npm install
# RUN npm ci --omit=dev
COPY . .

CMD ["npm", "run", "start"]

# RUN npm run build
# RUN node ./dist/index.js diff1
# RUN node ./dist/index.js diff2
# RUN node ./dist/index.js diff3
# RUN node ./dist/index.js diff4