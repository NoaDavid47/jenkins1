FROM node:16
WORKDIR /app

RUN npm install uuid

COPY main.js .

ENTRYPOINT ["node"]
CMD ["main.js"]
