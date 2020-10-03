# Webapp interviewing task

This app consists of a few modules:
- The [lib](https://github.com/Kaukov/fibonacci_app_lib) is a library used to
generate Fibonacci sequences and Fibonacci multiplication tables. For usage -
read its README.
- The [consoleapp](https://github.com/Kaukov/fibonacci_app_consoleapp) is a
console application that utilizes the Fibonacci lib and outputs a Fibonacci table
based on the user input. For its usage - read its README.
- The [backapp](https://github.com/Kaukov/fibonacci_app_backapp) is a backend
API that utilizes the Fibonacci lib to send a Fibonacci table as a response
and optionally save it in a database if the POST endpoint is hit. For usage
and more information - read its README.
- The [frontapp](https://github.com/Kaukov/fibonacci_app_frontapp) is the frontend
that consumes the backapp and visually outputs a Fibonacci multiplication
table with a user-specified size. For more information - read its README.

## To clone this repo and its submodules

```sh
git clone https://github.com/Kaukov/fibonacci_app.git --recurse-submodules
```
