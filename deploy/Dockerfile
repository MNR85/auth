FROM node:16
WORKDIR /opt/devops/account-manager

COPY package*.json ./

RUN npm install
# If you are building your code for production
# RUN npm ci --only=production

# Bundle app source
COPY . .
