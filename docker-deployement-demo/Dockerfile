# Use an official Node.js runtime as the base image
FROM nginx:alpine

COPY /build /usr/share/nginx/html

EXPOSE 80

# # Set the working directory in the container
# WORKDIR /app

# # Copy package.json and package-lock.json to the working directory
# COPY package*.json ./
# COPY package-lock.json ./

# # Install dependencies
# RUN npm install

# # Copy the entire project to the working directory
# COPY . .

# # Build the React app
# RUN npm run build

# # Set the environment variable to serve the app
# ENV NODE_ENV=production

# # Expose the port the app will run on
# EXPOSE 3000

# # Specify the command to start the app
# CMD ["npm", "start"]
