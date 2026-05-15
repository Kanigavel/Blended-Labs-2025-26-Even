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
**Screenshot:**  
<img width="1266" height="684" alt="3" src="https://github.com/user-attachments/assets/2df1ceb6-4468-4581-af77-1a58d098db73" />
<img width="1265" height="611" alt="1" src="https://github.com/user-attachments/assets/66b90234-ec58-4e05-bfe6-82ce94dbcce9" />
<img width="1298" height="771" alt="5" src="https://github.com/user-attachments/assets/ac25f05b-4879-40ff-850e-b7534056fc58" />


### Task 2: Add Users to Groups
- Added user-1 to the S3-Support group  
- Added user-2 to the EC2-Support group  
- Added user-3 to the EC2-Admin group  
**Screenshot:**  
  <img width="1259" height="658" alt="4" src="https://github.com/user-attachments/assets/0c9ab12f-174e-46cb-a65f-31c13ba8cad8" />
<img width="1238" height="644" alt="2" src="https://github.com/user-attachments/assets/9eb5cd80-7a74-407b-9866-a9e8394165a1" />
<img width="1301" height="780" alt="6" src="https://github.com/user-attachments/assets/3dac5984-6251-46a8-b703-495127e93b1d" />


### Task 3: Test IAM User Permissions
- Logged in using IAM sign-in URL  
- Verified S3 access for user-1  
- Verified EC2 read-only access for user-2  
- Verified EC2 administrative access for user-3  
**Screenshot:**  

<img width="1530" height="780" alt="12" src="https://github.com/user-attachments/assets/f777e8b5-b205-483b-87cb-1559a83f9de3" />
<img width="1259" height="727" alt="7" src="https://github.com/user-attachments/assets/5a3c0b99-4d7a-4f1e-938c-bacb29b94b78" />
<img width="1536" height="868" alt="18" src="https://github.com/user-attachments/assets/cb333279-5b68-4a11-b3d1-8966a12330ff" />


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
**Name:** Kanigavel M 212224240070
**Course:** Introduction to Cloud Computing  

