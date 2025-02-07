FROM node:16
WORKDIR /app
COPY package*.json ./
RUN pnpm install
COPY . .
EXPOSE 5000
CMD ["pnpm", "start"]