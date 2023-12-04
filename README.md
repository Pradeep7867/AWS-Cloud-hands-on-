# AWS-Cloud-hands-on-
## Overview: Demonstrates a virtual network with two 16-IP subnets, deploying an app on a VM with NACLs/SGs. Also features app deployment on Elastic Beanstalk and a Lambda function printing S3 file names upon upload. Explore for network, VM, AWS Beanstalk, and Lambda insights.


This project showcases a simple infrastructure setup for deploying and managing applications in a secure virtual network. It includes:

- **Virtual Network**: Configured with two subnets, each allowing 16 IPs, utilizing NACLs and SGs for enhanced security.

- **VM Deployment**: A virtual machine in one subnet hosting a sample application, demonstrating network isolation.

- **Elastic Beanstalk**: Deployment of the same application to AWS Elastic Beanstalk, emphasizing ease of deployment and scalability.

- **AWS Lambda Function**: Triggered on S3 file uploads, the Lambda function prints the uploaded file names in real-time.

## Project Structure

- `/network-setup`: Contains configurations for the virtual network, including subnets, NACLs, and SGs.

- `/vm-deployment`: Includes the VM setup and the application code for local deployment.

- `/beanstalk-deployment`: Holds the necessary files for deploying the application on AWS Elastic Beanstalk.

- `/lambda-function`: Contains the code and configurations for the Lambda function triggered by S3 file uploads.

## Getting Started

Follow the instructions in each directory to set up and deploy the components. Ensure you have the required dependencies and AWS credentials.

## Contributing

Feel free to contribute by opening issues or submitting pull requests. We welcome any improvements or additional features.

## License

This project is licensed under the [AWS license management](LICENSE).

