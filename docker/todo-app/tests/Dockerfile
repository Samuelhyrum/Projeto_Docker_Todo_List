FROM mjgargani/puppeteer:trybe1.0

ADD node_modules.tar.gz .
COPY /e2e .
COPY package.json .
COPY package-lock.json .
COPY jest.config.js .

CMD ["npm","tests"]
