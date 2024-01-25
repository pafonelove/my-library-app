# 2024-01-25 Ramazanov: frontend docker file
FROM node:18-alpine

WORKDIR /app

EXPOSE 3000

COPY ["package.json", "package-lock.json*", "./"]

RUN npm install

COPY . .

CMD ["npm", "start"]