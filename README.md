# Hello

1. `sbt runAll`
1. Get default greeting for Alice:
    - `curl http://localhost:9000/api/hello/World`
1. Change greeting for Alice:
    - curl -H "Content-Type: application/json" -X POST -d '{"message": "Hi"}' http://localhost:9000/api/hello/Alice
1. Get new greeting for Alice:
    - `curl http://localhost:9000/api/hello/World`