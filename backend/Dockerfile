# Use Node.js official image as a base
FROM node:14

# Set the working directory
WORKDIR /app

# Copy package.json and package-lock.json
COPY package*.json ./

# Install dependencies
RUN npm install express cors

# Copy the application code
COPY . .

# Expose the port
EXPOSE 5000

# Start the application
CMD ["node", "server.js"]
