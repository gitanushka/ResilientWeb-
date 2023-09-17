
# ResilientWeb+

 
ResilientWeb+ is a robust web application deployed on Amazon Web Services (AWS) with a primary focus on achieving high availability, scalability, fault tolerance, security, and cost optimization. This project aims to ensure that the web application remains accessible and operational even in the face of hardware failures, network issues, or other potential disruptions.

## Features

-  High Availability
High availability is the cornerstone of ResilientWeb+. We have designed our infrastructure to minimize downtime, ensuring that your application is accessible to users around the clock. Our high availability strategies include the use of Amazon EC2, Amazon RDS, Elastic Load Balancing (ELB), Amazon S3, and Amazon CloudFront.
-  Scalability
The ability to scale resources up or down to meet changing demands is crucial for any modern web application. ResilientWeb+ employs scalable AWS services and auto-scaling configurations to handle varying levels of traffic efficiently. Our architecture ensures that your application can seamlessly handle increased workloads.
- Fault Tolerance and Disaster Recovery
In the unpredictable world of technology, failures can occur. ResilientWeb+ incorporates fault tolerance mechanisms to withstand potential disruptions. We employ redundancy and failover strategies using Amazon RDS, ELB, and Amazon S3 to ensure that your application remains resilient even in the face of hardware or software failures.
- Cost Optimization
Optimizing costs while maintaining a high-quality service is a constant concern for businesses. ResilientWeb+ is designed with cost-efficient principles in mind. We leverage services like Amazon S3 and Amazon CloudFront to reduce data transfer costs and utilize AWS cost optimization tools to monitor and manage expenses effectively.


## Tech Stack

**AWS Services** 

**Amazon EC2**: For scalable compute resources.                               
**Amazon RDS**: Providing a managed relational database service.    
**Elastic Load Balancing (ELB)**: Distributing incoming traffic across multiple EC2 instances for high availability.
**Amazon S3**: Secure and scalable object storage for static assets and data.   
**Amazon CloudFront**: Content delivery network for faster delivery of web content.   
**Virtual Private Cloud (VPC)**: Creating isolated network environments for enhanced security.



## Architecture Diagram

![Architecture_ResilientWeb+](https://github.com/gitanushka/ResilientWeb-/assets/77441008/da9c7e9a-40d7-4bf2-8507-15cc49a4ac22)



