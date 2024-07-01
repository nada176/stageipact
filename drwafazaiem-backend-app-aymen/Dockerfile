FROM node:20.5.0  

# Set the working directory inside the container
WORKDIR /drwafazaiem-backend-app-aymen

# Copy package.json and package-lock.json into the working directory
COPY package*.json ./

# Install npm dependencies
RUN npm install -f

# Copy the rest of the application code to the working directory
COPY . .

# Expose the port your application will run on
EXPOSE 6668

# Command to run your application
CMD ["node", "server.js"]
