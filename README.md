# Circuit Breaker
* [Circuit Breaker by Martin Fowler](http://martinfowler.com/bliki/CircuitBreaker.html)
  The basic idea behind the circuit breaker is very simple. You wrap a protected function call in a circuit breaker object, which monitors for failures. Once the failures reach a certain threshold, the circuit breaker trips, and all further calls to the circuit breaker return with an error, without the protected call being made at all. Usually you'll also want some kind of monitor alert if the circuit breaker trips.

* [Building microservices with Spring Cloud and Netflix OSS](http://callistaenterprise.se/blogg/teknik/2015/04/15/building-microservices-with-spring-cloud-and-netflix-oss-part-2/)

* [Release it:Design.and.Deploy.Production.Ready.Software](http://buhoz.net/public/books/computacion/desarrollo/metodologias/agiles/Release It Design and Deploy Production Ready Software 2007.pdf)

* [Spring Cloud Circuit Breaker tutorial](https://spring.io/guides/gs/circuit-breaker/)

# Netflix
* [Netflix Hystrix] (https://github.com/Netflix/Hystrix)
* [Netflix Hystrix Dashboard](https://github.com/Netflix/Hystrix/wiki/Dashboard)

# Run Hystrix Dashboard Docker image
```
$ docker run -d -p 8080:8080 --name md-hystrix-dashboard grissomsh/hystrix-dashboard:latest

```


[![](https://images.microbadger.com/badges/image/grissomsh/hystrix-dashboard.svg)](https://microbadger.com/images/grissomsh/hystrix-dashboard "Get your own image badge on microbadger.com")

