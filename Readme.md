# rabbitmq-mover

Example of moving messages from one queue to another in RabbitMQ.

./rabbitmq-mover -from='ecom--core--order-history-service.failed' -to='ecom--order-history-service.ecom1.order.changed.handle'