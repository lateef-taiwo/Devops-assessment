FROM node:alpine3.18
WORKDIR /app
COPY package*.json .
RUN npm install
COPY . .
ENV PORT 3000
EXPOSE ${PORT}
CMD ["npm", "run-script"]