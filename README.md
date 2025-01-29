# Vulnerability Management Project

## Objective
In this project I grew my cybersecurity skills by setting up and configuring Tenable Nessues to scan and identify vulnerabilities of devices in my network.

I configured a network scan against a metasploitable VM and Kali Linux VM I set up from previous projects.



### Skills Learned

- Vulnerability Management

### Tools Used

- Tenable Nessus
- Virtual Machines (VMWare Workstation)
- Metasploitable https://docs.rapid7.com/metasploit/metasploitable-2/

### Prerequisites 
- Hypervisor (I used VMWare Workstation)
- Clients on network that you have permission to scan


## Steps

### Step 1 - Download Tenable Nessus on Windows 10 VM

Download Nessus

![image](https://github.com/user-attachments/assets/184b84c4-2c50-446a-aa60-45ebddb65da2)

Install wizard

![image](https://github.com/user-attachments/assets/f70f9fa9-3bf8-4698-a20a-fab704f145b9)

Initialize

![image](https://github.com/user-attachments/assets/90f0a195-914c-49fb-9fdf-20e1c5048a19)

Wait for plugin to finish compiling

![image](https://github.com/user-attachments/assets/ff02ec37-a0f1-47be-8228-62b7a86b2246)

### Step 2 - Create test scan

Create basic network scan

![image](https://github.com/user-attachments/assets/11aaaf20-828f-4065-92b4-dd9f01d7a01f)

Take note of IPs you want to add to network scan:

*Kali Linux ip*

![image](https://github.com/user-attachments/assets/7065cd40-0288-4aaa-81a3-fc5f609eed40)

*Metasloitable ip*

![image](https://github.com/user-attachments/assets/23a72377-8df8-4c72-8603-16444e22e981)

Add ip to network scan

![image](https://github.com/user-attachments/assets/a4fbd982-12e8-47f4-bb62-c44f8226523b)

Change discovery scan type to all ports

![image](https://github.com/user-attachments/assets/e744b943-c898-4053-8d96-f23c606e5e45)

Change assesment scan type to web vulnerabilities

![image](https://github.com/user-attachments/assets/7d79eece-9f33-4e1e-98cf-42cea07f77b6)

Save scan

### Step 3 - Run scan and view results

Click on play to run scan 

![image](https://github.com/user-attachments/assets/8f8a0c79-a20c-44f1-a877-f1607bcd0c1d)

Once the scanning has complete click in the scan to view the results

![image](https://github.com/user-attachments/assets/028d84b1-9174-4f50-aecf-da398c1135a8)

![image](https://github.com/user-attachments/assets/28726349-d2ac-4516-9bf9-b760af059830)

Click into the vulnerability to view more details and a solution

![image](https://github.com/user-attachments/assets/ec13dc8b-c1e4-4bcd-8c52-aa0794d9d66f)

Click on report, to generate a vulnerability report

![image](https://github.com/user-attachments/assets/120e142f-4e28-40d4-871b-23a7a1d0a7c1)

![image](https://github.com/user-attachments/assets/cac625c3-0ed6-4fe4-ab80-0271801aced1)

Now with the report and vulnerability scan output I can go through and start remediating some vulnerabilities
