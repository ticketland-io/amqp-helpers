Local RabbitMQ
===

```
docker run -d --hostname local-rabbit \
--name local-rabbit \
-p 15672:15672 \
-p 5672:5672 \
-e RABBITMQ_DEFAULT_USER=user \
-e RABBITMQ_DEFAULT_PASS=password \
rabbitmq:3-management
```
