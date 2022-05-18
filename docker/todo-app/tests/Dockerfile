FROM mjgargani/puppeteer:trybe1.0
WORKDIR /app
ADD node_modules.tar.gz .
RUN npm install
COPY . .
CMD ["npm", "test"]

