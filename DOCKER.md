# Running Docker

There is a ready to use docker-compose.
You can run tests in the docker using following steps:

1. docker-compose build
2. docker-compose run playwright bash - to enter into the container shell
3. npx playwright test - to run the tests
4. See the result :)

or just to run the tests

1. docker-compose build
2. docker-compose run playwright npx playwright test
3. See the result :)
