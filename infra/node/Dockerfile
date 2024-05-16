FROM node:16

RUN npm init -y
RUN npm install -g @nestjs/cli
RUN npx nest new app --package-manager=npm

WORKDIR /app

EXPOSE 3000
