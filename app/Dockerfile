FROM node:16

ENV NODE_ENV=production

# Create /usr/app directory
WORKDIR /usr/app

# Install dependencies
COPY package.json .
RUN npm install --production --quiet

# Copy source files
COPY . .

# Run the app
EXPOSE 3000
CMD ["npm", "start"]
