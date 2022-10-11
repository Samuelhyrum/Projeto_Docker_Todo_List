FROM mjgargani/puppeteer:trybe1.0
WORKDIR /todo-app/tests
ADD node_modules.tar.gz .
ADD /e2e .
ADD jest.config.js .
ADD jest.config.js .

CMD ["npm","tests"]
