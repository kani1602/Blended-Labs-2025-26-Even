# Lab 1 - Introduction to AWS Identity and Access Management (IAM)

## Title
Introduction to AWS Identity and Access Management (IAM)


## Objective
The objective of this lab is to understand how AWS Identity and Access Management (IAM) controls authentication and authorization in AWS. The lab focuses on exploring IAM users and groups, analyzing attached policies, assigning users to appropriate groups based on organizational roles, and validating permissions by testing service access.


## Prerequisites
- Basic understanding of cloud computing concepts  
- AWS Academy Lab access  
- Web browser with internet connectivity  


## Tools Used
- AWS Management Console  
- AWS Identity and Access Management (IAM)  
- Amazon EC2  
- Amazon S3  


## Tasks Performed

### Task 1: Explore IAM Users and Groups
- Reviewed pre-created IAM users: user-1, user-2, user-3  
- Explored IAM groups: EC2-Admin, EC2-Support, S3-Support  
- Inspected managed and inline policies attached to groups  
### Task 2: Add Users to Groups
- Added user-1 to the S3-Support group  
- Added user-2 to the EC2-Support group  
- Added user-3 to the EC2-Admin group  
**Screenshot:**  
<img width="1917" height="1077" alt="Screenshot 2026-08-06 213211" src="https://github.com/user-attachments/assets/1197d735-ec64-4dc1-be24-8b07eb882d40" />
<img width="1917" height="1091" alt="Screenshot 2026-08-06 213248" src="https://github.com/user-attachments/assets/ef0d0752-abf3-4967-852e-5326e292d8fa" />
<img width="1917" height="1077" alt="Screenshot 2026-08-06 213313" src="https://github.com/user-attachments/assets/d7dcc345-680b-4ed3-9e98-cf873578574a" />




### Task 3: Test IAM User Permissions
- Logged in using IAM sign-in URL  
- Verified S3 access for user-1  
- Verified EC2 read-only access for user-2  
- Verified EC2 administrative access for user-3  
**Screenshot:**  
<img width="1917" height="1076" alt="Screenshot 2026-08-06 213642" src="https://github.com/user-attachments/assets/8ffb3859-2e30-4147-8ed5-3a3f2f9cac03" />
<img width="1917" height="1083" alt="Screenshot 2026-08-06 213740" src="https://github.com/user-attachments/assets/169123af-2f39-49c2-bbdc-c7889c868b2b" />
<img width="1917" height="1077" alt="Screenshot 2026-08-06 214029" src="https://github.com/user-attachments/assets/869b0f1d-0337-4ea7-918c-c44fa2153a0a" />
<img width="1917" height="1082" alt="Screenshot 2026-08-06 214235" src="https://github.com/user-attachments/assets/404928f0-6e0a-4ad8-9157-c9d3e0dd4567" />



## Workflow
1. Accessed IAM console and reviewed users and groups.  
2. Inspected policy permissions attached to groups.  
3. Assigned users to groups based on their roles.  
4. Logged in as each IAM user using the sign-in URL.  
5. Validated permissions by accessing AWS services.  


## Learning Outcomes
- Understood the role of IAM in AWS security.  
- Learned how IAM users, groups, and policies interact.  
- Gained practical experience implementing role-based access control.  
- Verified permission enforcement through real-time service testing.  


## Conclusion
This lab provided hands-on experience with AWS IAM by demonstrating how organizations manage secure access to cloud resources. Assigning users to groups with predefined policies simplified permission management and ensured role-based access control across AWS services.


## Author
**Name:** Your Name and (Reg No)
**Course:** Introduction to Cloud Computing  

