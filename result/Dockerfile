FROM node:12-alpine
WORKDIR "/app/result"
COPY ./app /app/result
RUN npm i --production
EXPOSE 80
CMD npm start
