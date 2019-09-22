# Build stage

FROM node:alpine 

WORKDIR /nav-app/

# copy over needed files
COPY . ./

# install packages and build 
RUN npm install --unsafe-perm

EXPOSE 4200

CMD npm start
