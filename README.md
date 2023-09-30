# Build-a-Serverless-Web-Application
![image](https://github.com/pporumbescu/Build-a-Serverless-Web-Application/assets/60489736/224a5624-09de-44bf-86ed-d7052c9e1f3f)

Build a Serverless Web Application
September 29, 2023
Build a Serverless Web Application
Project details​
Overview
Welcome to my project, where I’ll guide you through the creation of a serverless web application designed to request unicorn rides from the Wild Rydes fleet. This straightforward yet captivating web app empowers users to select their pickup location, submit ride requests, and even register and log in to enhance their experience.

Application architecture
The application architecture uses AWS Lambda, Amazon API Gateway, Amazon DynamoDB, Amazon Cognito, and AWS Amplify Console. Amplify Console provides continuous deployment and hosting of the static web resources including HTML, CSS, JavaScript, and image files which are loaded in the user’s browser. JavaScript executed in the browser sends and receives data from a public backend API built using Lambda and API Gateway. Amazon Cognito provides user management and authentication functions to secure the backend API. Finally, DynamoDB provides a persistence layer where data can be stored by the API’s Lambda function.

The backbone of this application leverages the power of AWS services, including AWS Lambda, Amazon API Gateway, Amazon DynamoDB, Amazon Cognito, and AWS Amplify Console:

1. Static Web Hosting: AWS Amplify seamlessly hosts all static web resources, including HTML, CSS, JavaScript, and images, ensuring a smooth user experience.

2. User Management: Amazon Cognito takes care of user management and authentication, safeguarding our backend API.

3. Serverless Backend: Amazon DynamoDB acts as the reliable persistence layer for data storage, seamlessly integrated with our API’s Lambda function.

4. RESTful API: The frontend, executed in the user’s browser, communicates with a public backend API built using Lambda and API Gateway, enabling dynamic data exchange.

Please visit my website and read the entire post. https://petruclouds.com/build-a-serverless-web-application/
