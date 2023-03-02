# Specify base image
FROM node:6.14-slim

# Copy Everything
COPY ./index.js /index.js
COPY ./package.json /package.json

# Install dependencies
RUN npm install

# Default command
CMD ["npm", "start"]