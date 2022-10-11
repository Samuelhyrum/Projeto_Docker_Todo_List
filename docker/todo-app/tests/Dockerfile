FROM mjgargani/puppeteer:trybe1.0
WORKDIR /todo-app/tests
ADD node_modules.tar.gz .
COPY /e2e .
COPY jest.config.js .
COPY jest.config.js .

CMD ["npm","tests"]
