# Tata Connect Project - Tata Technologies Internship

This repository contains the complete solution for the **Tata Connect Project**, which I developed during my internship at **Tata Technologies**. The goal of the project was to replace a pre-existing outsourced solution (Viva-Engage) with an in-house communication platform, providing better scalability, resilience, and cost efficiency.

## Key Features and Achievements:
- **Tech Stack**: React (Frontend), Node.js (Backend), MySQL (Database).
- **AWS Integration**: Utilized AWS ECS and EC2 for scalable deployment and AWS RDS for database management.
- **Infrastructure as Code**: Deployed and managed the entire infrastructure using **Terraform**, enabling automated, consistent environments.
- **CI/CD Pipeline**: Streamlined the development process using **AWS CodePipeline**, ensuring smooth continuous integration and deployment.
- **Scalability**: Enhanced data scalability and resilience by **25%** using MySQL on AWS RDS.
- **Cost Efficiency**: Reduced infrastructure costs by **20%** through optimized deployment strategies and efficient resource management.
- **Project Outcome**: Saved **10-12% annually** by eliminating the need for the previous outsourced solution (Viva-Engage).

## Technologies Used:
- **Frontend**: React.js
- **Backend**: Node.js, Express
- **Database**: MySQL hosted on AWS RDS
- **Cloud Services**: AWS ECS, EC2, RDS
- **Infrastructure as Code**: Terraform
- **Continuous Integration/Deployment**: AWS CodePipeline

## How It Works:
1. **Frontend**: Built with **React**, the front-end application enables seamless communication, featuring real-time updates and user-friendly navigation.
2. **Backend**: The backend, developed in **Node.js** with **Express**, handles user requests, authentication, and database interactions.
3. **Database**: **MySQL**, hosted on **AWS RDS**, provides robust data management, ensuring high availability and scalability.
4. **Deployment**: The application is deployed on **AWS ECS** and **EC2**, with infrastructure defined using **Terraform** for consistency across environments.
5. **CI/CD**: Automated deployments are managed using **AWS CodePipeline**, ensuring fast and reliable updates to the production environment.

## Key Improvements:
- **Data Scalability**: With the use of **AWS RDS**, the system can now handle a larger volume of user data, improving resilience by 25%.
- **Cost Savings**: By migrating from an outsourced solution to an in-house one, infrastructure costs were reduced by 20%, and the company saved 10-12% annually on subscription fees.
  
## Installation and Setup:
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/tata-connect-project.git
   ```
2. Install dependencies:
   ```bash
   cd tata-connect-project
   npm install
   ```
3. Set up environment variables for AWS services, MySQL, and Terraform configurations.
4. Run the application locally:
   ```bash
   npm start
   ```

## Deployment:
Deployment is handled via **AWS ECS** and **EC2**, with Terraform scripts available in the `infra/` directory. Use the provided **Terraform** scripts to deploy the infrastructure automatically.

## License:
This project is licensed under the MIT License. See the [LICENSE](./LICENSE) file for more details.

---
