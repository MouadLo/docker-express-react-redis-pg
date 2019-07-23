# Docker and NodeJs

## Fib-calc
A multicontainer and "complicated" version of a Fibonacci calculator. It runs on a Nginx server,uses React for the frontend
and Express for the backend API. All calculated values get stored in a Postgres database and it uses Redis for the logs.
A worker process watches Redis for new indexes and calculates the Fibonacci value. 