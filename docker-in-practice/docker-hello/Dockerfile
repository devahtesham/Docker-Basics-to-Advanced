# STEP: 01 First we need to specify base image to run our application, so we need to run js file so we need nodejs runtime to execute this file. so with FROM command we'll install nodejs version 20-alpine (which is a lightweight linux based)
FROM node:20-alpine

# STEP:02 specify the working directory
WORKDIR /app

# STEP:03 need to copy every thing from the current directory to docker image. In below command first dot(.) denote the current directory and the second one is denoting the current directory path in the container
COPY . .

# STEP:04 specify the command to run this application.
CMD node index.js

