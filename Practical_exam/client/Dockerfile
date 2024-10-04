# Use the official Node.js image as a base
FROM node:16-alpine

# Set working directory
WORKDIR /app

# Copy the frontend code
COPY . .

# Install dependencies
RUN npm install

# Expose port 4173
EXPOSE 4173

# Start the Vite development server
CMD ["npm", "run", "dev"]
