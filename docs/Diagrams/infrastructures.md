
# Udagram App Infrastructure
This documentation is aimed to combine both app dependencies and pipeline together to result in the final desirable output

## Deployment Diagram
<img src="https://github.com/atf01/udagram-project/blob/main/docs/Diagrams/Arch.png">

- as shown in the Diagram above the first AWS component to create is to RDS so as to host our database and to be consumed by the Application APIs.
- The second AWS Component that depends on the RDS is Elastic Beanstalk which hosts our Backend API that consumes the Database hosted by RDS.
- The Third AWS Component that represents the main interface with end users is the S3 Bucket which consumes the APIs provided by the backend 
