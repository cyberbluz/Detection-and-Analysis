# Never pass up an opportunity to breakout copies of NIST and your Organizatioinal Playbook

![image](https://github.com/user-attachments/assets/44f84a02-6a02-4b87-b4b2-62cc5c91570c) 
![image](https://github.com/user-attachments/assets/ca01ee74-43f8-453a-82c0-54dc79899f84)
![image](https://github.com/user-attachments/assets/4d031cdc-024e-47c0-8a1c-8b457e96ea9e)

## In this phase of the project, I will use NIST 800-61 Incident Handling Guide and work through several Alerts created by MS Sentinel, and refer to my Playbook for a Brute Force Success response plan.

![image](https://github.com/user-attachments/assets/2bce92d2-1902-4b68-998c-e0de062a0ac0)
----
----
![image](https://github.com/user-attachments/assets/3e8b4036-60db-4022-ab4a-8d00727df6dc)
----
----
![image](https://github.com/user-attachments/assets/35b06032-eeac-47dc-adef-b7170a13f521)
## Further investigation revealed (as documented in my Incident Notes) that incidents 66 and 47 were from the same ip address along with several other Brute Force attempts.  I also found that the “Brute Force Success” alerts were in fact False Positives created by a service account. The indication was that the Host VM was suffering from overexposure to inbound traffic and the Firewall (NSG) may be misconfigured.  

## Using the same procedure, I worked through all the alerts in preparation for the Eradication & Recovery phase of the process. 
#  - [Eradicate & Recovery](https://github.com/cyberbluz/Eradicate-and-Recovery)
----
----
