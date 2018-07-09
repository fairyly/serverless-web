# serverless-web
serverless-web

无服务器框架 - 使用AWS Lambda，Azure功能，Google CloudFunctions等构建无服务器架构的Web，移动和IoT应用程序！

- github: https://github.com/serverless/serverless#readme
- doc: https://serverless.com/framework/docs/
- website: https://serverless.com/

```
GitHub 登录:

myapp-dev
You haven’t deployed any services to this application yet.

Install the Serverless Framework
Install the Serverless Framework via Node.js and NPM:

$ npm install -g serverless
Log in to the Serverless Platform.

$ serverless login
The Serverless Framework needs access to your cloud provider's account so that it can create and manage resources on your behalf. The Serverless Docs will walk you through how to do this painlessly.

Configure and deploy your Service
A Service is a group of related serverless functions and infrastructure resources declared by a serverless.yml file. It can either contain your entire Application, or you can split your Application across multiple Services, to maintain better separation of concerns. If you do not have an existing Serverless Framework Service, create one by running this command in a new folder.

$ serverless create -t aws-nodejs
In your serverless.yml file, be sure to add your Serverless Platform Application and Tenant, like this:

service: my-service
app: myapp-dev
tenant: fairyly
 
provider:
  name: aws
  runtime: nodejs4.3
 
functions:
  hello:
    handler: handler.hello
Now deploy your Service and check back here.

$ serverless deploy
For more information check out the Getting Started guide in our docs.
```
