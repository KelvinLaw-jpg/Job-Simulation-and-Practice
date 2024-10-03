# Cybersecurity Workshop by Telstra

```
Aim: 
- Practice what day to day job of an analyst on Mastercard’s Security Awareness Team
- Helped identify and report security threats such as phishing 
- Analyzed and identified which areas of the business needed more robust security training and implemented training courses and procedures for those teams

Description:
Task 1: Examine an obvious fake email and make it more believable 
Task 2: Design a short presentation to educate staffs on Phishing attempts
```

## Task 1-Responding to a malware attack

#### Background
```
You are an information security analyst in the Security Operations Centre.A common task and responsibility of information security
analysts in the SOC is to respond to triage incoming threats and respond appropriately, by notifying the correct team depending on
the severity of the threat. It’s important to be able to communicate the severity of the incident to the right person so that
the organisation can come together in times of attack.

The firewall logs & list of infrastructure has been provided, which shows critical services that run the Spring Framework and need
to be online / uninterrupted. A list of teams has also been provided, which depending on the severity of the threat, must be contacted.
It’s important to note that the service is down and functionality is impaired due to the malware attack.
```
#### Task objective
```
Your task is to triage the current malware threat and figure out which infrastructure is affected.
First, find out which key infrastructure is currently under attack. Note the priority of the affected
infrastructure to the company - this will determine who is the respective team to notify.

After, draft an email to the respective team alerting them of the current attack so that they can begin an incident response.
Make sure to include the timestamp of when the incident occurred. Make it concise and contextual.

The purpose of this email is to ensure the respective team is aware of the ongoing incident and to be prepared for mitigation advice.
```

---

1.2 According to the above, the following changes are suggested for a more convincing phishing email

```
From: mastercardIT@gmail.com
To: employee@email.com 
Subject: System Update - Password Reset Required

Body: 

To All Mastercard Staffs,

The IT department has patched the system and server firmware due to risk of compromise. It will require all staffs to reset and update their password.

Please click [here](https://en.wikipedia.org/wiki/Phishing) to update your password in the next hour or your account will be locked. Please contact the IT support regarding to any problem during log in. 
 
Regards,
Mastercard IT Department

Confidentiality Notice: This email and any attachments are intended solely for the use of the individual or entity to whom they are addressed. If you are not the intended recipient, you are hereby notified that any dissemination, distribution, copying, or use of this communication is strictly prohibited. If you have received this email in error, please notify the sender immediately and delete it from your system.
```

1. Ideally, the source should not have gmail as domain name, but if so then spelling the organisation name correct is important
2. Instead of URGENT, trying to give a proper reason which requires the staff to reset or update their password is more convincing
3. Greeting line changed
4. Instead of showing the link, the link is masked the the word `click here`
5. A line after the malicious link is added as a buffer and extra support is given. Thus, the link is more likely to be true
6. Simple confidentiality disclaimer is added at the end for extra legitimacy

---

### Task 2

The email is sent to everyone in the company and a tool is used to analyze the result (failure rate of each department)
Below is the result:

| Team  | Email open rate   | Email click-through rate   | 	Phishing success rate|
|------------|------------|------------|------------|
| IT| 80%| 2%|0%|
| HR| 100%| 85%|75%|
| Card Services| 60%| 50%|10%|
| Reception| 40%| 10%|0%|
| Engineering| 70%| 4%|1%|
| Marketing| 65%| 40%|38%|
| R&D| 50%| 5%|2%|
| Overall| 66%| 28%|18%|

- Email open rate = the percentage of people that opened it
- Email click-through rate = the percentage of people that clicked on the link
- Phishing success rate = the percentage of people that clicked the link and inputted some personal information

According to the Data, HR and Marketing department are very prone to phishing attempt, therefore, you are asked to make a short presentation to inform them on milicious emails.

---

[Presentation](Links/Phishing_presentation_example.pdf)
