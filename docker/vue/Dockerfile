# FROM node:8.16-alpine   

# RUN apk update && \
#     npm install && \
#     npm install -g @vue/cli 

FROM node:12

WORKDIR /usr/src/app

# COPY package*.json ./

RUN npm install && \
    npm install -g @vue/cli 

# COPY . .

# EXPOSE 8080

# CMD [ "node", "server.js" ]