# Capstone - Master in Cloud Computing 2304VCCO - IMMUNE
This is the final project of the Master in Cloud Computing 2304VCCO in IMMUNE, this repository contains what is needed to deploy Wordpress in AWS.

*Top level and first level hierarchy of nested stacks.*

![top-level](https://user-images.githubusercontent.com/53886913/219972549-17ba8b71-3e53-4282-bd7d-c0af7f8732e2.png)

*The following diagram represents high level overview of the infrastructure:*

![capstone-arq-V2 0 0 drawio](https://github.com/andres-pulecio/master-capstone/assets/53886913/d1f6edee-48c9-40fe-a88d-e287e6ccb117)

## Description of the challenge

The company has determined that it needs to modernize the Backend to solve some of the problems
presented. Among his ideas, he has considered migrating it to the cloud and thus being able to take advantage of some
benefits that a cloud solution offers such as scalability, high availability, efficiency of
operations, among others.
It is required that you propose a cloud architecture and infrastructure solution that better resolves
measures the problems and has the following characteristics:
- Performance improvement
- Offering high availability
- That is scalable
- That optimizes infrastructure costs
- Allows the evolution of services and functionalities through partial deployments either by regions or by groups of the client portfolio
- Allows the addition of new functions in the future without affecting the services in operation
- Makes efficient use of assigned resources
- It have mechanisms that improve security aspects, ensuring that only users and Authorized applications can use web services

## How to execute?

1. All .yml files must be hosted in an S3 bucket
2. In cloud formation, load the main.yml and adjust to the necessary data, it is necessary that the name of the bucket created in step one be referenced in the data.

## This template create:
