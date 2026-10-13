# LetsDefend-Phishing-Email-Analysis-Internal-to-Internal

## Phishing Mail Detected 

### Practice with SOC Alert

### SOC120 - Phishing Mail Detected - Internal to Internal

---

<img width="1909" height="608" alt="image" src="https://github.com/user-attachments/assets/4047135d-1c11-45f5-b9b9-990a49e6e4c6" />

Here is My assigned Ticket, seating in my Investigation Channel; ready to be investigated

---

* Click Details to view more information about the Ticket.

<img width="1899" height="781" alt="image" src="https://github.com/user-attachments/assets/9d492cce-ef31-487a-b831-e7281ad484c5" />

* Click >> Create Ticket to Create ticket for EventID: 52

<img width="1909" height="656" alt="image" src="https://github.com/user-attachments/assets/4c3cff3f-9882-4232-b509-b0911ea0ecfc" />

* Click the blue Continue button to create a ticket

* Click OK when the window pops up “Ticket Created” indicating my “The ticket has been created successfully.”

<img width="789" height="528" alt="image" src="https://github.com/user-attachments/assets/404f056f-11c7-4cc8-956a-479fa231f500" />

---

### Play Book Opens

Which is used to begin the guided incident response investigation for this specific SOC120 - Phishing Mail Detected - (Internal to Internal) alert.
<img width="1912" height="588" alt="image" src="https://github.com/user-attachments/assets/4bd85bd0-553b-4ae2-9e2e-31eff17df2d1" />

This screen highlights a critical security alert:

• Incident Name: SOC120 - Phishing Mail Detected - (Internal to Internal)

• Incident Type: Exchange

• Created Date: 2026-10-13 18:42:31

The dashboard indicates that I am currently navigating within the Case Management section (highlighted on the left panel).

* Click blue **Start Playbook!** button.

---

<img width="904" height="479" alt="image" src="https://github.com/user-attachments/assets/ec2a6ccb-7db7-468f-b1c5-4df9f288029f" />

* When was it sent:                            

* What is the email's SMTP address:      172.16.20.3

* What is the sender address:            john@letsdefend.io

* What is the recipient address:         susie@letsdefend.io

---

* Click Email Security

* Type **Sender Address** to filter and view the email details.

<img width="1905" height="802" alt="image" src="https://github.com/user-attachments/assets/941d4fbd-41af-40a5-a140-106633a483a0" />

<img width="1897" height="738" alt="image" src="https://github.com/user-attachments/assets/c28fcad5-6a21-4ba7-8209-d62b1c8f2f4c" />

* Click **No**

<img width="984" height="390" alt="image" src="https://github.com/user-attachments/assets/10a4196c-ccd1-4750-a182-88159c09a326" />

* Is the mail content suspicious: **No**

* Are there any attachment: **No**

### Reason:

There are no attachments or URLs included in this email. Because this is an internal communication between coworkers with standard formatting, the content itself does not contain traditional phishing artifacts.

---

### Artifact 1: Sender IP

• Value: 172.16.20.3

• Type: IPv4 (or IP)

• Comment: Sender IP address from the email header.


### Artifact 2: Sender Email

• Value: john@letsdefend.io

• Type: Sender Email

• Comment: Sender email address.

### Artifact 3: Recipient Email

• Value: @letsdefend.io

• Type: Email Domain

• Comment: Company Email Domain address.

<img width="945" height="544" alt="image" src="https://github.com/user-attachments/assets/728185d6-571b-498e-960a-b88e84c550df" />

---

### Analyst Note
```
Investigated the alert regarding a potential internal phishing email sent from john@letsdefend.io to susie@letsdefend.io. 

Analysis Details:
- The email header shows the sender IP as 172.16.20.3.
- The email subject is "Meeting" and contains basic text coordinating availability.
- No malicious links, URLs, attachments, or scripts were found within the body of the email.

Conclusion:
The communication contains no malicious indicators or phishing vectors and represents normal organizational behavior. The alert is a False Positive.
```

<img width="935" height="451" alt="image" src="https://github.com/user-attachments/assets/307cae41-4292-48f8-86ae-f05979a35ede" />

---

* Click Confirm & Close

* Select **False Positive**

To officially submit and close out this case (Ticket)

<img width="946" height="353" alt="image" src="https://github.com/user-attachments/assets/1b194516-5c4d-4b29-8305-d94d3b5899ee" />

---
