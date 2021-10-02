Module 6 - Security
================


About
------------
I have need to focus on lessons last 2 weeks, achieve lessons one after others. When writing this summary, i'm currently study Module 7 - Monitoring and analytics. So i have to go back into my OneNote workbook in order to go back in my mind ;-)\
This module deals with Amazon security concepts such aShared Security Model, Identity ans Access Management (IAM), Compilance, DDoS, cryptography and several firewalling services.

Hight light of the part
--
1. Module 6 introduction
2. Shared responsibility model
3. User permissions and access
4. AWS Organizations
5. Compliance
6. Denial-of-service attacks
7. Additional security services
8. Module 6 summary
9. Module 6 quiz

Summary
--
Ths module present AWS and customers role of each parts to secure hosted cloud environment, called Shared Responsability Model. AWS secure the IaaS, until the cloud service layer, the customer secure all above from the operating system to the data. 
![image](https://user-images.githubusercontent.com/79169883/135729524-64ab7503-07da-40f3-8113-ab7c96e44b1b.png)

The second part present AWS Identity and Access Management, IAM which allow to build security with users, groups, policies, multi-factor authentication, identities and roles. This part provide best practice to secure the root account. 
Identity and Access Management | Users | Groups | MFA | Roles |
| :---: | :---: | :---: | :---: | :---:
|![image](https://user-images.githubusercontent.com/79169883/135730275-606d991f-35f8-4736-8054-1dc292bf69c0.png)| ![image](https://user-images.githubusercontent.com/79169883/135730398-83f195e7-881e-4c2b-988c-090f18690a6c.png) | ![image](https://user-images.githubusercontent.com/79169883/135730410-ae1e8c3d-4969-4179-a200-934ea1538573.png) | ![image](https://user-images.githubusercontent.com/79169883/135730448-41660534-7ccd-4e40-be2a-4ed35b616c64.png) | ![image](https://user-images.githubusercontent.com/79169883/135730478-e7afce75-0ca9-49c2-8819-fd8e0875b104.png) | 

WHen having multiple AWS accounts, customers can use AWS Organisations in order to federate management of all accounts.

AWS Organisations | Organizational Units |
| :---: | :---: 
|![image](https://user-images.githubusercontent.com/79169883/135730578-ee8e6f9c-8c4b-4138-be39-2763f7f8234f.png)|![image](https://user-images.githubusercontent.com/79169883/135730601-56afed8a-9093-45c7-9f01-99aa8726f5e1.png)|

Amazon bring compilance tools, AWS Artifacts and AWS Compilance Center to help AWS customers to ensure they are up to compilance with regulation of their business is helded to.
AWS Artifacts | AWS Compilance Center |
| :---: | :---:
|![image](https://user-images.githubusercontent.com/79169883/135730651-312d771a-1e8a-4864-a3dc-89a640df13a7.png)|[AWS Compilance Center](https://aws.amazon.com/fr/compliance/customer-center/ "AWS Compilance Center")|

In last sections, course introduce with DOS and DDoS (Denial of Service, Distributed Denial of Service) security components such as Securituy Groups (seen in module 4), Elastic Load Balancer, AWS Shield and AWS WAF (Web Application Firewall), AWS Inspector and GuardDuty Shield (Standard and Advanced).
AWS Web Application Firewall | AWS Shield | AWS Key Management Service | AWS Inspector | AWS GuardDuty |
| :---: | :---: | :---: | :---: | :---:
|![image](https://user-images.githubusercontent.com/79169883/135730836-999ce5af-feb5-48bc-a712-074c8a7df5e4.png)|![image](https://user-images.githubusercontent.com/79169883/135730847-77731bbf-b224-4f3a-9327-86020c4d5841.png)|![image](https://user-images.githubusercontent.com/79169883/135730861-888aeeb6-3f4f-4149-b646-d473d40c99aa.png)|![image](https://user-images.githubusercontent.com/79169883/135730876-ad482187-f56d-468d-96fe-02557a62f31a.png)|![image](https://user-images.githubusercontent.com/79169883/135730894-71cc9981-ca49-41d4-a829-79c3dca83fa3.png)| 

Quick notes
--
Just make a copy past of end additionnals ressources.\
I found them usefull.

* [Security, Identity, and Compliance on AWS](https://aws.amazon.com/fr/products/security/ "Security, Identity, and Compliance on AWS")
* [Whitepaper: Introduction to AWS Security](https://docs.aws.amazon.com/whitepapers/latest/introduction-aws-security/welcome.html "Whitepaper: Introduction to AWS Security")
* [Whitepaper: Amazon Web Services - Overview of Security Processes](https://docs.aws.amazon.com/whitepapers/latest/aws-overview-security-processes/aws-overview-security-processes.pdf "Whitepaper: Amazon Web Services - Overview of Security Processes")
* [AWS Security Blog](https://aws.amazon.com/fr/blogs/security/ "AWS Security Blog")
* [AWS Compliance](https://aws.amazon.com/fr/compliance/ "AWS Compliance")
* [AWS Customer Stories: Security, Identity, and Compliance](https://aws.amazon.com/fr/solutions/case-studies/?customer-references-cards.sort-by=item.additionalFields.publishedDate&customer-references-cards.sort-order=desc&awsf.customer-references-location=*all&awsf.customer-references-segment=*all&awsf.customer-references-product=product%23vpc%7Cproduct%23api-gateway%7Cproduct%23cloudfront%7Cproduct%23route53%7Cproduct%23directconnect%7Cproduct%23elb&awsf.customer-references-category=category%23security-identity-compliance "AWS Customer Stories: Security, Identity, and Compliance")

