# Go RESTful API with MySQL, Validation, and Testing

## Overview

This Go application is a RESTful API that demonstrates the integration of various key components:

- **Database**: It connects to a MySQL database using the `go-sql-driver/mysql` driver for data storage and retrieval.

- **Validation**: The API uses the `go-playground/validator` package for request data validation, ensuring that data sent to the server meets predefined criteria.

- **Routing**: HTTP routing is handled by the `julienschmidt/httprouter` router, allowing you to define clean and efficient routing for your API endpoints.

- **Testing**: Unit tests are included in the project using `stretchr/testify` to ensure the correctness and reliability of the API's functionality.

## Prerequisites

Before you can run this API, make sure you have the following installed:

- Go (Golang): [Installation Guide](https://golang.org/doc/install)
- MySQL: [Installation Guide](https://dev.mysql.com/doc/mysql-installation-excerpt/5.7/en/)

## Getting Started

1. Clone the repository:
   ```bash
   git clone https://github.com/prasetyodidi/golang-restful-api.git
2. Navigate to the project directory:
   ```bash
   cd golang-restful-api
3. Install project dependencies:
   ```bash
   go get github.com/go-sql-driver/mysql
   go get github.com/julienschmidt/httprouter
   go get github.com/go-playground/validator/v10
   go get github.com/stretchr/testify
4. Set up your MySQL database:
   - Create a MySQL database and configure the connection details in database.go.
5. Build and run the application:
   ```bash
   go run main.go
## API Specification
The API endpoints and request/response formats are defined in the apispec.yaml file. You can find the detailed API specification there.
## Unit Testing
Unit tests are available in the *_test.go files. Run tests using:
   
   ```bash
   go test
   ```
## Conclusion
This Go RESTful API project demonstrates the integration of MySQL, validation, routing, and unit testing to create a robust API for managing categories. Feel free to extend and modify it to suit your specific requirements.

Happy coding!