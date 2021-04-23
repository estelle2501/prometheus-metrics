This project demonstrates how to expose Prometheus metrics of SpringBoot application.

Prerequisites: apache-maven-3.6.3, openjdk version "15.0.1"

In order to start, just run PrometheusDemoApplication class.

URL for Prometheus metrics: http://localhost:8080/actuator/prometheus

Test endpoint: http://localhost:8080/hello
Number of executed calls to "/hello" endpoint will be incremented in metric:
http_server_requests_seconds_count{exception="None",method="GET",outcome="SUCCESS",status="200",uri="/hello",}

