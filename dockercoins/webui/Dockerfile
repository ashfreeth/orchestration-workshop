FROM brunswickheads/hello-nodejs-s390x
RUN npm install express
RUN npm install redis
COPY files/ /data/files/
COPY webui.js /data/
CMD ["node", "webui.js"]
EXPOSE 80
