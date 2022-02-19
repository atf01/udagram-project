# App dependencies

## Development Dependencies

### Nodejs
it's a platform that runs all javascript/typescript based frameworks.
### there're more to know about it through:
- [Documentation](https://nodejs.org/en/docs/)
-
#### Deployment Dependencies (AWS Console)

this documentation will walk you throguh the necessary steps of creating the required resources to deploy the udagram web application

### RDS

it's a service that enables us to host our database and provide an endpoint for our web APIs 

After creating and configuring the database to be publicly accessible the final result should be as depicted in the image below:-

<img src="https://github.com/atf01/udagram-project/blob/main/docs/AWS%20Screens/RDS%20creation.PNG">

### Elastic Beanstalk

it's a service that's aimed to simplify the process of creating a a server to host the backend API endpoints for the web application

After creating and deploying the API on the server you may notice that the API health is OK which indicates that the server is configured correctly.
the image below shows the expected result after a successful configuration of the Elastic beanstalk server

<img src="https://github.com/atf01/udagram-project/blob/main/docs/AWS%20Screens/Elastic%20beanstalk%20env%20created.PNG">

### S3 Bucket

it's a service that's aimed to host our project files, it's created by default by elastic beanstalk when creating and configuring a new server.
S3 bucket can be configured to host our frontend due to the fact that our build results in a collection of html,css and javascript files that works the same way as our frontend app.
the image below depicts the correct result of uploading our frontend files on its corresponding s3 bucket named udagram-frontend

<img src="https://github.com/atf01/udagram-project/blob/main/docs/AWS%20Screens/frontend%20app%20uploaded.PNG">

and the this image shows the overall buckets created for either the frontend and the backend

<img src="https://github.com/atf01/udagram-project/blob/main/docs/AWS%20Screens/S3%20Buckets.PNG">


