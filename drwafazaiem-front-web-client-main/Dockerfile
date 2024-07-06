# Base image
FROM node:20.5.0-alpine

# Set the working directory inside the container
WORKDIR /App

# Copy package.json and package-lock.json to the working directory
COPY package*.json ./

# Install dependencies
RUN npm install -f
# Install webpack globally
RUN npm install -g webpack

# Copy the source code to the working directory
COPY drwafazaiem-front-web-client-main/ .


# Expose any necessary ports (if applicable)
EXPOSE 5555

 # Default command to run the application (if applicable)
CMD [ "npm","start" ]

