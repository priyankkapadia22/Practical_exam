# Use the official Node.js image as a base
FROM node:16-alpine

# Set working directory
WORKDIR /app

# Copy the backend code
COPY . .

# Install dependencies
RUN npm install

# Expose port 3000 for the backend
EXPOSE 3000

# Start the server
CMD ["npm", "start"]
