#Development ONLY

# BASE IMAGE
FROM node:alpine

#Working DIR
WORKDIR '/app'

#COPY Dependencies folder
COPY ./package.json ./

#Install dependencies
RUN npm install

#COPY EVerything to the image
COPY . . 

#start up command
CMD ["npm", "run", "start"]