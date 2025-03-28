AWS CI/CD Pipeline with CodeDeploy
Overview
This project demonstrates an automated CI/CD pipeline using AWS CodePipeline, CodeDeploy, and EC2 for deploying applications. The pipeline ensures seamless application deployment by integrating with GitHub, AWS services, and a well-defined deployment process.

Note: Use Userdata script to create to install Dependencies on EC2 (via User Data script): 
This script installs: 
o Ruby (required by CodeDeploy agent), 
o Wget (for downloading installation files), 
o CodeDeploy agent, 
o Python pip and AWS CLI (for managing AWS resources).



