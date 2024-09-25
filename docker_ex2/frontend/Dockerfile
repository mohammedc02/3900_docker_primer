# Use the Node 14 base image
FROM node:14

# Set the working directory in the container
WORKDIR /usr/src/app

# Copy all files from the current directory to the working directory in the container
COPY . .

# Install dependencies using yarn
RUN yarn install

# Expose port 3000 (commonly used by frontend applications)
EXPOSE 3000

# Specify the command to run the frontend
CMD ["yarn", "start"]
