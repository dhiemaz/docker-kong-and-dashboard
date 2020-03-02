# Docker compose for Kong API Gateway and Dashboard
Docker compose for running Kong API gateway along with Kong dashboard

## Requirement
* Operating System (MacOS, Windows, Linux)
* Docker (tested with version 19.03.5)

## How to run
* If you haven't installed docker inside your operating system, then you must install it first. To install docker, please refer to docker installation which you can easily find on the internet.

* If you have installed docker in your operating system, then you can run using `docker-compose` command.

```bash
$docker-compose up
```

or

```bash
$docker-compose -f "docker-compose.yml" up
```

## FAQ (Frequently Asked Questions)
_Q_ : I am facing an issue "ERROR: for kong-dashboard  Container "b59f0c0c21e4" is unhealthy." what should I do?

_A_ : You can try creating these folders `kong` or `postgresql` in the same folder with `docker-compose.yml` file, check whether it solve the issue. Here I was facing the same issue and creating those folder solve it.





