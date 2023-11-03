# Dockerfile to setup node

# from which image
FROM node:12
# copy app over
COPY app/app .

# get pm2
RUN npm install pm2 -g

ENV DB_HOST=http://localhost:27017/posts

# port 3000
EXPOSE 3000

# CMD specific instructions
RUN npm install
RUN npm remove mongoose
RUN npm install mongoose@4.10.8 --save
RUN node seeds/seed.js
RUN pm2 start app.js
CMD ["node", "app.js"]
