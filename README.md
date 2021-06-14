## Week 16 Homework Submission File: Penetration Testing 1

#### Step 1: Google Dorking


- Using Google, can you identify who the Chief Executive Officer of Altoro Mutual is: 
`site:altoromutual.com intext:Chief Executive Officer`

- How can this information be helpful to an attacker: _**The google dorking techniques help find potential targets alot quicker further enumaration on this target could be useful in planning a attack.**_


#### Step 2: DNS and Domain Discovery

Enter the IP address for `demo.testfire.net` into Domain Dossier and answer the following questions based on the results:

  1. Where is the company located: _**US**_

  2. What is the NetRange IP address: _**65.61.137.64 - 65.61.137.127**_

  3. What is the company they use to store their infrastructure: _**Rackspace Backbone Engineering**_

  4. What is the IP address of the DNS server: _**23.211.61.64**_

#### Step 3: Shodan

- What open ports and running services did Shodan find: _**53**_

#### Step 4: Recon-ng

- Install the Recon module `xssed`. 
- Set the source to `demo.testfire.net`. 
- Run the module. 
![alt text](https://github.com/tomdixonn/Homework_16/blob/main/recon-ng.JPG)

- Is Altoro Mutual vulnerable to XSS: 
![alt text](https://github.com/tomdixonn/Homework_16/blob/main/report.JPG)

 

### Step 5: Zenmap

Your client has asked that you help identify any vulnerabilities with their file-sharing server. Using the Metasploitable machine to act as your client's server, complete the following:

- Command for Zenmap to run a service scan against the Metasploitable machine: 
 
- Bonus command to output results into a new text file named `zenmapscan.txt`:

- Zenmap vulnerability script command: 

- Once you have identified this vulnerability, answer the following questions for your client:
  1. What is the vulnerability:

  2. Why is it dangerous:

  3. What mitigation strategies can you recommendations for the client to protect their server:

---
© 2020 Trilogy Education Services, a 2U, Inc. brand. All Rights Reserved.  
