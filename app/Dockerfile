FROM node:10
WORKDIR /application
ADD package.json .
RUN npm install
ADD . ./
EXPOSE 1234
# RUN sleep 20
# RUN npm install -g nodemon
# RUN npm install -g forever
# CMD forever --spinSleepTime 10000 --minUptime 5000 -c "nodemon --exitcrash -L --watch /application/" /application/app.js
CMD ["node","/application/app.js"]