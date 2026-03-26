https://github.com/DilakshanMadhusanka/github-actions-learning/actions/runs/23590208858

https://github.com/DilakshanMadhusanka/github-actions-learning/actions/runs/23590379124

https://github.com/DilakshanMadhusanka/github-actions-learning/actions


PS C:\Users\user\Desktop\github-actions-learning\github-actions-learning\sample-app> npm test


> github-actions-sample-app@1.0.0 test
> jest --coverage
> github-actions-sample-app@1.0.0 test
> jest --coverage

> jest --coverage


 PASS  tests/server.test.js
 PASS  tests/server.test.js
  GET /
    √ should return welcome message (39 ms)
  GET /api/hello
    √ should return hello message (14 ms)
  GET /api/hello
    √ should return hello message (14 ms)
    √ should return hello with custom name (11 ms)
    √ should return hello message (14 ms)
    √ should return hello with custom name (11 ms)
    √ should return hello with custom name (11 ms)
  GET /api/status
  GET /api/status
    √ should return health status (10 ms)
  POST /api/data
    √ should accept data and return uppercase (41 ms)
    √ should return 400 if text is missing (7 ms)
  GET /health
    √ should return health check (14 ms)
  404 handler
    √ should return 404 for unknown routes (10 ms)

-----------|---------|----------|---------|---------|-------------------
File       | % Stmts | % Branch | % Funcs | % Lines | Uncovered Line #s
-----------|---------|----------|---------|---------|-------------------
All files  |   82.75 |    66.66 |      75 |   82.75 |
 server.js |   82.75 |    66.66 |      75 |   82.75 | 60-61,66-68
-----------|---------|----------|---------|---------|-------------------
Test Suites: 1 passed, 1 total
Tests:       8 passed, 8 total
Snapshots:   0 total
Time:        1.645 s, estimated 2 s
Ran all test suites.

