# Use official Node.js image
FROM node:18-slim

# Set working directory
WORKDIR /usr/src/app

# Copy package.json and app.js
COPY package.json ./
COPY app.js ./

# Install dependencies
RUN npm install --only=production

# Start the application
CMD ["npm", "start"]
