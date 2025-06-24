# Analyzing-Phishing-Email-Sample
This repository contains analyzing a sample phishing email to identify common phishing tactics.

# Objective
The goal of this task is to analyze a suspicious email, detect potential phishing characteristics.

# Disclaimer
This repository is for educational and internship purposes only. The phishing email used here is a simulated sample and does not represent a real attack.

# Tools used
Caniphish Simulator(Sample Email Source): (https://caniphish.com)

# Summary of the Phishing Email
- Email Type: Netflix Password Reset Scam  
- Fake Sender: netflix@webnotifications[.]net  
- Urgency Trigger: "Password expires in 3 days"  
- Suspicious Link: Redirects through a fake "Reset Password" button  
- Grammar Issue: Unprofessional phrasing, grammatically incorrect (e.g., “Netflix are requesting...”)

# Key Indicators of Phishing
-Spoofed sender domain
-Urgent and alarming language
-Mismatched or hidden URLs
-Grammar and spelling errors
-Unusual domain not owned by the real company

Since, the sample phishing email which I have used does not contain any email header, so I have taken help from AI asking it to give a sample header for a fake Netflix phishing email so that I could learn about checking email headers for discrepancies . I will attach the screenshot of it.
# Header Field and Suspicious Finding
-SPF: fail – Domain not authorized to send email
-DKIM: fail – No signature verification
-DMARC: fail – Domain policy indicates message should be rejected
-Received from: Unknown mail server IP (103.89.200.15) not tied to Netflix

# Conclusion
The email mimics Netflix branding but contains multiple phishing traits, including a spoofed sender domain, urgent messaging, mismatched link, and failed email authentication (SPF, DKIM, DMARC). It is clearly a phishing attempt aimed at stealing user credentials.





