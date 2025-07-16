# Base image
FROM node:18

# Create app directory
WORKDIR /app

# Install app dependencies
COPY package*.json ./
RUN npm install

# Copy app source
COPY . .

# Expose and start the app
EXPOSE 3068
CMD ["node", "server.js"]

