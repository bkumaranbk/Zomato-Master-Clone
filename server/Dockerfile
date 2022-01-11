FROM node:alpine

WORKDIR /app
COPY ./package.json ./
RUN npm install
COPY . .

ENV MONGO_URL=mongodb+srv://kumaranbk:kumaranbk13517@zomoto-master.jscga.mongodb.net/myFirstDatabase?retryWrites=true&w=majority
ENV GOOGLE_CLIENT_ID=196872282729-2k7p068gc0cgsjafksrekmio7jln43f2.apps.googleusercontent.com
ENV GOOGLE_CLIENT_SECRET=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
ENV AWS_S3_ACCESS_KEY=AKIAX5O6M5YQ6YAIP5WB
ENV AWS_S3_SECRET_KEY=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
ENV NODE_ENV=production
ENV PORT=5000


CMD ["npm", "run", "start"]