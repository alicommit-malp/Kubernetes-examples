FROM node 
WORKDIR /src/node/app
COPY package.json ./

RUN npm install 
COPY . .

EXPOSE 3000
CMD ["npm","strat"]