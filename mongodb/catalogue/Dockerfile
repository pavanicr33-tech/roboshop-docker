FROM almalinux:20
# create /app and set the directory to /app
WORKDIR /app
COPY package.json .
COPY *.js .
ENV MONGO_URL="mongodb://mongodb:27107//catalogue"\
    MONGO="true"
CMD ["node","server.js"]