# Swagger

This application was generated using JHipster 4.0.7, you can find documentation and help at [https://jhipster.github.io/documentation-archive/v4.0.7](https://jhipster.github.io/documentation-archive/v4.0.7).

This is a "microservice" application intended to be part of a microservice architecture, please refer to the [Doing microservices with JHipster][] page of the documentation for more information.


## Documentation

In order to generate the documentation, run:

    mvnw test swagger2markup:convertSwagger2markup install


## Development

To start your application in the dev profile, simply run:

    ./mvnw


## Building for production

To optimize the application for production, run:

    ./mvnw -Pprod clean package

To ensure everything worked, run:

    java -jar target/*.war


Refer to [Using JHipster in production][] for more details.

## Testing

To launch your application's tests, run:

    ./mvnw clean test

For more information, refer to the [Running tests page][].

