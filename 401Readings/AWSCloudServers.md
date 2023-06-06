# AWS Cloud Servers

## [AWS EC2](https://aws.amazon.com/ec2/)

What is an EC2 Instance?

- An EC2 Instance is a piece (virtual instance) of a server with a compute capacity e.g cpu % and ram % etc on the server. It can be configured with tools and programs and even run with a chosen OS. It is highly configurable with power, storage, and RAM options. It's essentially an extremely flexible and highly configurable server that you can control and use for apps and calculations etc.

Name 2 use cases for EC2.

- Run cloud applications, use scalable infrastructure with applications

Provide 1 reason to use ECS instead of a service such as Heroku, Digital Ocean, or Render.com.

- AWS Has a greater infrastructure and boast the greatest equipment. They probably also have a bigger support team and are capable of handling much greater loads across many various types of services.

## [EC2 For Humans](https://www.youtube.com/watch?v=lZMkgOMYYIg)

Where can we find EC2 on the AWS Console?

- Elastic Compute Cloud is found under the compute section in all services.

Explain the general difference between T2 Micro and XL.

- t2 micro is a plan made for very small traffic and the occasional spike. The t2 xl is a plan for major traffic and high hardware requirements

Explain a “Compute Cycle” to a non-technical friend.

- A compute cycle is the process of running instructions and the time it takes. In a game the home page has a different compute cycle than the battlefield. The process of executing instructions changes because different options are available and different things are visible. Running through the compute cycle may have different stages and events

## [Elastic Beanstalk](https://www.youtube.com/watch?v=SrwxAScdyT0)

What is Elastic Beanstalk?

- Bean stalk allows you to provision the management and scaling of web applications

Describe the relationship between EC2 and Elastic Beanstalk.

- EB Will leverage the server instance from EC2 and automatically handle provisiog load balancing, health monitoring, and auto scaling for control over the resources the server.

Name some benefits of using Elastic Beanstalk.

- Beanstalk lets you focus on building apps, websites, apis, SASS apps, etc by removing the extra steps to manage scaling etc, with no chagre. In fact managing these resources will maybe even improve the amount you pay per month
