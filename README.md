# rabbitmq
A simple rabbitmq image based on offical rabbitmq

## Run
```sh
docker run --rm -p 4369:4369 -p 5671:5671 -p 5672:5672 -p 25672:25672 -p 61613:61613 -d --hostname rabbitmq --name rabbit muaddib/rabbitmq
```
