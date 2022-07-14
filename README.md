# AMQP-Rust

# Connect/publish with/to AMQP
- https://www.zupzup.org/rmq-in-rust/
- lapin - AMQP client library (RabbitMQ) in rust - https://github.com/amqp-rs/lapin
- deadpool - Dead simple pool implementation for rust with async-await - https://github.com/bikeshedder/deadpool
- warp - web server framework - https://github.com/seanmonstar/warp


https://www.zupzup.org/rmq-in-rust/
https://github.com/zupzup/rmq-in-rust-example


## Docker installation - 

- sudo apt-get update
- sudo apt install docker.io
- docker --version
- sudo docker ps -az

- sudo dockerd

## Create Docker Container for RABBITMQ
- sudo docker run -p 15672:15672 -p 5672:5672 -e RABBITMQ_DEFAULT_USER=rmq -e RABBITMQ_DEFAULT_PASS=rmq  rabbitmq:3.8.4-management

## Run Code
- cargo run
