FROM node:12.22-alpine3.10

WORKDIR /app
EXPOSE 8080
CMD ["npm", "run", "dev"]

COPY package* ./
RUN npm ci
COPY . .
