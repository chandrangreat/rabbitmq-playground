# RabbitMQ Playground

This repository is to test out RabbitMQ.

Every branch has different functionalities.

To run this project you would need multiple terminal windows
One for sending message to queue and one for receiving messages fromt he queue.

This assumes that you are already running RabbitMQ in your system.

We are following this [link](https://www.rabbitmq.com/tutorials/tutorial-one-javascript) per branch. Main branch contains Hello-World

In this branch `worker-queues` you can run multiple workers using `node worker.js`. And then run tasks by running the below commands at once

```
node new_task.js First message.
node new_task.js Second message..
node new_task.js Third message...
node new_task.js Fourth message....
node new_task.js Fifth message.....
node new_task.js Sixth message.....
```

The periods tells us how many seconds does the task take to complete.
