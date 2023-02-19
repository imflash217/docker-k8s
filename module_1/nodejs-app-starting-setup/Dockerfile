FROM node
WORKDIR /app
COPY package.json /app
RUN npm install

COPY . /app
# same as this below
# COPY . .

# EXPOSE is only added for documentation; doesnot do anything. but recommended.
EXPOSE 80

# this CMD command is executed when the contaienr is run; not when it is being built.
CMD ["node", "server.js"]