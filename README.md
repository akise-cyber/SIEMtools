# SIEMtools

Google Activity - SIEM tools

Splunk

Review the following scenario. Then complete the step-by-step instructions.

You are a security analyst working at the e-commerce store Buttercup Games. You've been tasked with identifying whether there are any possible security issues with the mail server. To do so, you must explore any failed SSH logins for the root account.  

1. How many events are contained in the main index across all time?  Over 100,000 
2. Which field identifies the name of a network device or system from which an event originates? host 
3. Which of the following hosts used by Buttercup Games contains log information relevant to financial transactions? vendor sales 
4. How many failed SSH logins are there for the root account on the mail server? More than 100

Key takeaways In this activity, you used Splunk Cloud to perform a search and investigation. 
Using Splunk Cloud, you were able to: Upload sample log data 
Search through indexed data 
Evaluate search results 
Identify different data sources Locate failed SSH login(s) for the root account

Google Chronicle

Review the following scenario. Then complete the step-by-step instructions.

You are a security analyst at a financial services company. You receive an alert that an employee received a phishing email in their inbox. You review the alert and identify a suspicious domain name contained in the email's body: signin.office365x24.com. You need to determine whether any other employees have received phishing emails containing this domain and whether they have visited the domain. You will use Chronicle to investigate this domain.


1. According to the available ET Intelligence Rep List, how is signin.office365x24.com categorized?
    Drop site for logs or stolen credentials 
3. Which assets accessed the signin.office365x24.com domain? emil-palmer-pc coral-alvarez-pc roger-spence-pc 
4. Which IP address does the signin.office365x24.com domain resolve to?  40.100.174.34 
5. How many POST requests were made to the signin.office365x24.com domain?  2 
6. Some POST requests were made to signin.office365x24.com. What is the target URL of the web page that the POST requests were made to? http://signin.office365x24.com/login.php 
7. Pergunta 6 Which domains does the IP address 40.100.174.34 resolve to?  signin.office365x24.com signin.accounts-gooqle.com 


Key takeaways In this activity, you used Chronicle to investigate a suspicious domain used in a phishing email. Using Chronicle's domain search, you were able to: Access threat intelligence reports on the domain Identify the assets that accessed the domain Evaluate the HTTP events associated with the domain Identify which assets submitted login information to the domain Identify additional domains After investigation, you determined that the suspicious domain has been involved in phishing campaigns. You also determined that multiple assets might have been impacted by the phishing campaign as logs showed that login information was submitted to the suspicious domain via POST requests. Finally, you identified two additional domains related to the suspicious domain by examining the resolved IP address.
