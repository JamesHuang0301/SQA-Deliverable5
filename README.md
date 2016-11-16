#SQA-Deliverable5: Web Vulnerabilities Test
##xih55@pitt.edu

I use Acunetix Vulnerability Online Scanner in this deliverable
Test Website: http://testasp.vulnweb.com
    
Vulnerabilities:

Vulnerability 1:
    
Steps:
* Add scan target and select http://testasp.vulnweb.com
* Launch scan and wait for result
* Select Cross site scripting (verified) tag
* The details of this vulnerability will be shown
    
Screenshot of this vulnerability:
    
![image](https://github.com/JamesHuang0301/SQA-Deliverable5/blob/master/Screen%20Shot%202016-11-15%20at%2011.37.12%20PM.png)

1.What part of the InfoSec Triad does this vulnerability attack (confidentiality, integrity, or availability)?
* Confidentiality：Cookies and sessions can be taken by attacker
* Integrity：Attackers can modify contents of user account
* Availability：Attackers can steal user account and modify page contents

2.What kind of security attack can exploit this vulnerability (interruption, interception, modification, or fabrication)?
* Fabrication
* Interception

3.Are attacks that exploit this vulnerability active or passive?
* Active

4.What business value would be lost due to exploiting this vulnerability (data loss, unauthorized access, denial of service, etc)?
* Data loss：Cookies and sessions can be taken by attacker
* Unauthorized access：Attackers can steal user account
* Denial of service：Attackers can steal user account and modify page contents

5.What steps should the development team take to fix this vulnerability?
* Script should filter metacharacters from user input.

