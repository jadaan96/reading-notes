## AWS: API, Dynamo and Lambd
**1-What is Amazon API Gateway?**
It is a service offered by Amazon that functions as a replacement for conventional REST API servers on the backend. It allows you to define your routes and associate them with the required logic on Amazon Gateway, effectively managing HTTP requests.

**2-Why is Amazon API Gateway an important part of the Serverless ecosystem?**

>it’s like the link between the functions of Lambda and a functionless API server, to link them together to get a fully functionining serverless API.

**3-How does API Gateway integrate with other AWS services?**

It is integrated with various other services, including Lambda, SNS, IAM, and Cognito Identity Pools, enabling the management and configuration of authentication and authorization layers for APIs, especially when using Cognito.

With Lambda, it leverages function writing, enabling these functions to execute on the specified endpoints. As for SNS (Simple Notification Service), it facilitates notifications for the accessed API endpoint.

### AWS API Gateway
**1-What two API types might you choose from?**
1-RESTful API
2-Websocket API

**AWS DynamoDB Guide**
**What is DynamoDB?**
>a NoSQL database that amazon offers, it has the common NoSQL benefits of supporting scalable applications.

**Under what circumstances would you recommend DynamoDB over MongoDB?**
If you are using serverless API functionalities then Dynamo would give you the most suitable options because it’s integrated over AWS serverless services.

**Explain to a non-technical friend how DynamoDB works.**
>Imagine you have much of items all are similar types, like for example books, what way would you use to store it so it won’t be in danger of spoiling and how to access the book you want to read as fast as possible?, DynamoDB is like that super Library, it provides you that cabinet (of books) to store books in and label each book with (key) that you just use to take that book out of the cabinet, and it has already multi(workers) who would keep your books safe (serverless AWS serviceses).


#### Dynamoose
**1-What is Dynamoose?**
The tool is a modeling framework for Amazon DynamoDB, similar to Mongoose for MongoDB and Sequelize for PostgreSQL. It simplifies interactions, offers easier syntax, and provides built-in methods for shortcuts and streamlined functionalities.
**2-What are some key features of Dynamoose?**
* Type safety
* High-level API
* Easy-to-use syntax
* Support for DynamoDB Single Table Design
* Data transformation before saving or retrieval
* Strict data modeling with validation and required attributes.











