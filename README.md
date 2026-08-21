# Ex--10-IAM-working-overview
### Name: AKASH CT
### Reg No: 212224240007
### Aim
**To explore and configure AWS Identity and Access Management (IAM) users, groups, and policies, and to verify permissions for accessing Amazon S3 and Amazon EC2 resources.**
### Procedure
1. Start the AWS Lab and open the **AWS Management Console**.
2. Open **IAM → Users** and verify `user-1`, `user-2`, and `user-3`.
3. Open **User groups** and verify the groups **S3-Support, EC2-Support, and EC2-Admin** and their attached policies.
4. Add:

   * `user-1` → **S3-Support**
   * `user-2` → **EC2-Support**
   * `user-3` → **EC2-Admin**
5. Open the IAM **Sign-in URL** and sign in as each user using the given lab credentials.
6. Test `user-1`: verify **S3 access** and confirm **EC2 access is denied**.
7. Test `user-2`: verify **EC2 read-only access** and confirm that stopping an EC2 instance is denied; verify **S3 access is denied**.
8. Test `user-3`: open **EC2**, select `LabHost`, and **stop the instance** successfully.
9. Submit the lab and check the **Grades/Submission Report**.
10. End the lab after completing all tasks.
### Output

<img width="1917" height="1088" alt="Screenshot 2026-07-28 092403" src="https://github.com/user-attachments/assets/2f40e95a-58e5-4cf3-a372-9e80a24ec230" />
<img width="1917" height="1087" alt="Screenshot 2026-07-28 092432" src="https://github.com/user-attachments/assets/5e7a58ea-fc85-4bfb-9c08-08be9a178f14" />
<img width="1915" height="1087" alt="Screenshot 2026-07-28 092456" src="https://github.com/user-attachments/assets/1baacdb5-d866-4758-a1e5-07c7edf0aaf7" />
<img width="1917" height="1090" alt="Screenshot 2026-07-28 092517" src="https://github.com/user-attachments/assets/70abb73f-d121-44a2-b4fe-e742d4e4e88d" />

<img width="1917" height="1143" alt="Screenshot 2026-07-28 092530" src="https://github.com/user-attachments/assets/cbb8cfde-37cb-4522-9a02-fde16d3fe84c" />

<img width="1915" height="1086" alt="Screenshot 2026-07-28 092700" src="https://github.com/user-attachments/assets/7a16a614-0a96-48f3-b33a-54f22131178b" />

<img width="1917" height="1197" alt="Screenshot 2026-07-28 093355" src="https://github.com/user-attachments/assets/dc66da2f-4585-4956-81e7-bc6576ebf8d5" />

<img width="1917" height="1053" alt="Screenshot 2026-07-28 095610" src="https://github.com/user-attachments/assets/b8b05c29-a0e3-4114-a943-495ced2c0ded" />

<img width="1917" height="1091" alt="Screenshot 2026-07-28 100138" src="https://github.com/user-attachments/assets/e4d3273d-30bd-46c6-ac46-b2ef1ac543be" />

<img width="1917" height="1197" alt="Screenshot 2026-07-28 100150" src="https://github.com/user-attachments/assets/912334c7-2fa3-4522-a8e2-643b886d4136" />



### Result
The IAM users were successfully assigned to their respective groups, and the required permissions were verified. `user-1` received S3 read-only access, `user-2` received EC2 read-only access, and `user-3` received EC2 administrative access to start/stop instances. Thus, IAM users, groups, policies, and permissions were successfully explored and tested.
