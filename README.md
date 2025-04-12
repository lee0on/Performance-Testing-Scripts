## Overview
This repository contains performance test plans and resources designed to evaluate and measure the performance of various systems. The repository includes:

1. **Two test plans for HTTPS servers** - Load tests performed on public APIs: Swagger Petstore and Restful Booker.
2. **A database performance test plan for MySQL (Sakila schema)** - Simulates various database operations under load.
3. **An LDAP server performance test plan** - Tests the search, compare, add, modify, and delete operations of an LDAP server.

These test plans were developed using JMeter and include configurations, scripts, and run results.

---

## Project Structure

```
├── run-results
│   ├── myLDAP
│   ├── restful-booker
│   ├── sakila-db
│   ├── swagger-petstore
│
├── test-plans
│   ├── myLDAP
│   │   └── LDAP-load-test.jmx
│   ├── restful-booker
│   │   ├── resources
│   │   └── restful-booker-load-test.jmx
│   ├── sakila-db
│   │   ├── resources
│   │   └── sakila-load-test.jmx
│   ├── swagger-petstore
│       ├── resources
│       └── petstore-load-test.jmx
│
├── user-flows
```

### Folders and Files
1. **run-results**: Contains the output results of test runs for different systems.
   - **myLDAP**: Results of LDAP server performance tests.
   - **restful-booker**: Results of RESTful API performance tests.
   - **sakila-db**: Results of MySQL database performance tests.
   - **swagger-petstore**: Results of Swagger Petstore API performance tests.

2. **test-plans**: Contains JMeter test plans and resources.
   - **myLDAP**: Includes the `LDAP-load-test.jmx` file for LDAP server testing.
   - **restful-booker**: Includes a `resources` folder and `restful-booker-load-test.jmx` file for testing RESTful APIs.
   - **sakila-db**: Includes a `resources` folder and `sakila-load-test.jmx` file for MySQL database testing.
   - **swagger-petstore**: Includes a `resources` folder and `petstore-load-test.jmx` file for Swagger Petstore API testing.

3. **user-flows**: A placeholder folder for future user journey simulations.

---

## Future Updates
In the future, I plan to expand this repository by adding:

1. **Performance tests for FTP servers** - Evaluate the upload/download performance and concurrency of FTP servers.
2. **Performance tests for JMS (Java Message Service)** - Analyze the throughput and latency of message queues.
3. **Functional tests for HTTPS servers** - Include functional scenarios alongside performance testing to ensure reliability under load.
4. **Adding user flows** - Populate the corresponding folder with user journey simulations.
5. **Stress tests and stability tests** - Extend the scope of testing to include scenarios with extreme loads and long durations.

Stay tuned for updates!
