
# specify the default image 
FROM node:20-alpine3.17

# specify the current working directory

WORKDIR /my-app

# copy all the source files 

COPY . .
# run all dependencies at build time
RUN npm install
# specify the port 

EXPOSE 4000

CMD ["node","server.js"]
# BUILD IMAGE
