[![Build Status](https://travis-ci.org/LearnToCodeSeoul/calculator.svg?branch=master)](https://travis-ci.org/LearnToCodeSeoul/calculator)

# Calculator
> Simple calculator written in Java

# Screenshot
![screenshot](docs/img/calc.png)

## How to run
- Mac O/S, Linux
```
$ ./mvnw spring-boot:run
```
- Windows
```
$ mvnw.cmd spring-boot:run
```

## How to test

### Server API
- Plus
```
$ curl "http://localhost:8080/plus?first=1&second=2"
```
- Minus
```
$ curl "http://localhost:8080/minus?first=2&second=1"
```
- Divide
```
$ curl "http://localhost:8080/divide?first=2&second=1"
```
- Multiply
```
$ curl "http://localhost:8080/times?first=2&second=1"
```

- Multiply with calculate
```
$ curl "http://localhost:8080/calculate/times?first=2&second=1"
```
