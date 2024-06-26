# Base image
FROM node:16.20.0

# Set the working directory inside the container
WORKDIR /drwafazaiem-backend-app-aymen

# Copy package.json and package-lock.json to the working directory
COPY package*.json ./

# Install dependencies
RUN npm install --legacy-peer-deps

# Install webpack globally
RUN npm install -g webpack

# Copy the source code to the working directory
COPY . .


# Expose any necessary ports (if applicable)
EXPOSE 3444

 # Default command to run the application (if applicable)
CMD [ "npm","start" ]
