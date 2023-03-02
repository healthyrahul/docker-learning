# Specify base image
FROM node:6.14-slim

# Copy Everything
WORKDIR '/app'

COPY package.json .

# Install dependencies
RUN npm install
COPY . .

# Default command
CMD ["npm", "start"]