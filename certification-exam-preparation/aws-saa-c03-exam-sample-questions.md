# AWS Certified Solutions Architect Exam (SAA-C03) - Sample Questions

## Exam Overview
👉 Level: Associate </br>
👉 Length: 130 minutes to complete the exam </br>
👉 Cost: 150 USD </br>
👉 Format: 65 questions, either multiple choice or multiple response </br>
👉 Delivery method: Pearson VUE testing center or online proctored exam </br>
👉 For more details, refer [official documentation>>](https://aws.amazon.com/certification/certified-solutions-architect-associate/) </br>

## Sample Questions

- <b>*Question-01:*</b> Novatec Incorporation, an automobile company would like to build a new car-as-a-sensor service by leveraging fully serverless components that are provisioned and managed automatically by AWS. 
The development team at the carmaker does not want an option that requires the capacity to be manually provisioned, as it does not want to respond manually to changing volumes of sensor data. Given these constraints, which of the following solutions is the BEST fit to develop this car-as-a-sensor service?
     1. Ingest the sensor data in Kinesis Data Streams, which is polled by an application running on an EC2 instance and the data is written into an auto-scaled DynamoDB table for downstream processing
        
     2. Ingest the sensor data in an Amazon SQS standard queue, which is polled by a Lambda function in batches and the data is written into an auto-scaled DynamoDB table for downstream processing
     3. Ingest the sensor data in an Amazon SQS standard queue, which is polled by an application running on an EC2 instance and the data is written into an auto-scaled DynamoDB table for downstream processing
     4. Ingest the sensor data in Kinesis Data Firehose, which directly writes the data into an auto-scaled DynamoDB table for downstream processing

- <b>*Question-02:*</b> Novatec Incorporation is looking for a solution with high availability, as it plans to migrate its critical application to a fleet of Amazon EC2 instances. The solution should allow for content-based routing as part of the architecture. As a Solutions Architect, which of the following will you suggest for the company?
     1. Use an Auto Scaling group for distributing traffic to the EC2 instances spread across different Availability Zones. Configure an Elastic IP address to mask any failure of an instance
     2. Use an Application Load Balancer for distributing traffic to the EC2 instances spread across different Availability Zones. Configure Auto Scaling group to mask any failure of an instance
     3. Use an Auto Scaling group for distributing traffic to the EC2 instances spread across different Availability Zones. Configure a Public IP address to mask any failure of an instance
     4. Use a Network Load Balancer for distributing traffic to the EC2 instances spread across different Availability Zones. Configure a Private IP address to mask any failure of an instance

