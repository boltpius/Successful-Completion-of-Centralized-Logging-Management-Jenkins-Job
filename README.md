# Successful-Completion-of-Centralized-Logging-Management-Jenkins-Job

This task involved setting up a centralized logging management system to maintain and analyze server logs easily. The goal was to gather Apache logs from one of the app servers to identify and troubleshoot any issues that arise. To accomplish this, a Jenkins job named "copy-logs" was created and configured to run every 3 minutes.

The job utilized the SSH plugin to enable SSH access to the app server (App Server 3) and executed the SCP command to copy the Apache logs (access_log and error_log) from the default logs location. The logs were then transferred to the /usr/src/security location on the storage server.

To ensure seamless transfer without requiring a password, SSH key generation was performed on the app server, and the public keys were sent to the storage server using SSH copy ID.

By automating this process with Jenkins, the DevOps team at xFusionCorp Industries can regularly collect server logs and efficiently analyze them for troubleshooting purposes.

Please find the attached screenshot of the completed task 

<img width="1509" alt="Screenshot 2023-09-09 at 14 16 46" src="https://github.com/boltpius/Successful-Completion-of-Centralized-Logging-Management-Jenkins-Job/assets/127052041/52a514cb-409d-429c-915b-87d7bd68e80f">
<img width="1509" alt="Screenshot 2023-09-09 at 14 23 27" src="https://github.com/boltpius/Successful-Completion-of-Centralized-Logging-Management-Jenkins-Job/assets/127052041/69aed1fa-7d05-49d4-ab78-c73a050c04f3">
<img width="1509" alt="Screenshot 2023-09-09 at 14 27 40" src="https://github.com/boltpius/Successful-Completion-of-Centralized-Logging-Management-Jenkins-Job/assets/127052041/8ec94833-7e2f-4495-a1ff-bee457636838">
<img width="1509" alt="Screenshot 2023-09-09 at 14 27 59" src="https://github.com/boltpius/Successful-Completion-of-Centralized-Logging-Management-Jenkins-Job/assets/127052041/2db8ec6b-3a93-4953-aac3-0363dba65ebc">
<img width="1509" alt="Screenshot 2023-09-09 at 14 28 06" src="https://github.com/boltpius/Successful-Completion-of-Centralized-Logging-Management-Jenkins-Job/assets/127052041/a6806e6e-a3ef-4c0e-867d-53ffabce3f32">
<img width="1509" alt="Screenshot 2023-09-09 at 14 28 17" src="https://github.com/boltpius/Successful-Completion-of-Centralized-Logging-Management-Jenkins-Job/assets/127052041/804d73d3-4181-4154-b3ee-c2c043515804">



