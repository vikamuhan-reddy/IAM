# EX - 6 Implementation Of IAM

## Aim

To implement identity and access management (IAM) in AWS to securely control access to resources by creating and managing IAM users, groups, roles, and policies for team collaboration.

## Algorithm

1. Sign in to the AWS Management Console.
2. Navigate to the IAM service.
3. Create IAM groups with defined policies (e.g., Admin, Developer).
4. Create IAM users and assign them to appropriate groups.
5. Create IAM roles if cross-account or service-based access is needed.
6. Attach permissions using managed or custom policies.
7. Enable MFA (Multi-Factor Authentication) for users.
8. Monitor access using IAM Access Analyzer and CloudTrail.

## Procedure
1. Start the lab, wait for the AWS icon to turn green, and open the AWS Management Console.
2. In the console, go to IAM, explore Users (user-1, user-2, user-3) and their permissions.
3. Check User groups: EC2-Admin, EC2-Support, S3-Support; view attached policies and permissions.
4. Add users to groups based on their roles: user-1 → S3-Support, user-2 → EC2-Support, user-3 → EC2-Admin.
5. Confirm each group has 1 user assigned in the Users column.
6. Copy the IAM sign-in URL for testing users.
7. Sign in as user-1 (S3 support) in a private browser; verify S3 access and restricted EC2 access.
8. Sign in as user-2 (EC2 support); verify EC2 read-only access and restricted S3 access.
9. Sign in as user-3 (EC2 admin); verify ability to stop/start EC2 instances.
10. Close the private browser, return to the lab, and Submit your work.
11. Wait for grading, review Submission Report for feedback.
12. End the lab and close all panels.


## Output

<img width="960" height="515" alt="Screenshot 2025-10-27 094208" src="https://github.com/user-attachments/assets/545984aa-f52a-4080-8f85-c58d83ae05ff" />

<img width="960" height="515" alt="Screenshot 2025-10-27 094019" src="https://github.com/user-attachments/assets/47173162-f306-424a-bf9c-92cfd9c37831" />


## Result

Successfully implemented identity and access management using Amazon IAM for secure team collaboration and controlled access to AWS resources.
 
