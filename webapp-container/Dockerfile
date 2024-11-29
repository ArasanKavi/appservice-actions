FROM node:20
WORKDIR /app
COPY ./webapp-container/package.json ./
COPY ./webapp-container .
EXPOSE 3000
CMD ["npm", "run", "build"]
