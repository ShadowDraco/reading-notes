# AWS SNS and SQS

## [AWS SQS vs SNS](https://medium.com/awesome-cloud/aws-difference-between-sqs-and-sns-61a397bf76c5)

1.  What is the difference betweeen SQS and SNS?

SNS is a distributed _Publish-Subscribe_ service while SQS is a distributed _queuing_ service.
SNS is a distributed publish-subscribe system. Messages are pushed to subscribers as and when they are sent by publishers to SNS.
SNS supports several end points such as email, sms, http end point and SQS. If you want unknown number and type of subscribers to receive messages, you need SNS.

SQS is distributed queuing system. Messages are not pushed to receivers. Receivers have to poll SQS to receive messages. Messages can be stored in SQS for short duration of time (max 14 days).

Messages can’t be received by multiple receivers at the same time. Any one receiver can receive a message, process and delete it. Other receivers do not receive the same message later. Polling inherently introduces some latency in message delivery in SQS unlike SNS where messages are immediately pushed to subscribers.

2.  What are some use cases for both SNS and SQS?

Choose SNS if:

You would like to be able to publish and consume batches of messages.
You would like to allow same message to be processed in multiple ways.
Multiple subscribers are needed.
Choose SQS if:

You need a simple queue with no particular additional requirements.
Decoupling two applications and allowing parallel asynchronous processing.
Only one subscriber is needed.

## [AWS SNS and SQS](https://www.youtube.com/watch?v=mXk0MNjlO7A)

1.  Describe how to use SQS and SNS in a "fanout" pattern.

SNS will send messages to subscribers by 'fanning out' the messages to all of the subscribers. SQS does not fanout the queue to many people becasue SQS is typically made for single consumers per queue

2.  Explain how "push notifications" work, using SNS.

SNS push notifications fan out a message to different subscribers, like the people who did not volunteer to recieve spam emails. When the sender sends their message it runs a function that sends to each subscriber through some medium by which they are subscribed. Like Email.

## [SQS and SNS Basics](https://www.youtube.com/watch?v=UesxWuZMZqI)

1.  How might a large scale, distributed application make use of a Queue system like SQS?

a large scale application is used to create a buffer between the application and the consumer, providing the ability to process many responses from a large amount of customers in the order they were received without losing the requests.

### Reflection

Tommorow worjing with these queues and message systems will be pretty cool, nd it seems to not be as complex and scary as it may seem at first