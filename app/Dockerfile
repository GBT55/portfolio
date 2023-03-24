FROM node:19.8
# FROM node:19.8-alpine

# Create a directory for the app
WORKDIR /app

# Copy package.json and package-lock.json
COPY package*.json ./

# Install dependencies
RUN npm install

# Copy the rest of the application
COPY . .

# Expose the port
EXPOSE 3000

# Start the app
CMD ["npm", "start"]