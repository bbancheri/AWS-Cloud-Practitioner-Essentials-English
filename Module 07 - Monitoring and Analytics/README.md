Module 7 - Monitoring and Analytics
================


About
------------
From mdoule 7 to 11, as summarysed in module 6, i study all module without append sections in github.
This module present AWS ressources that monitor analyse you AWS account : `CloudWatch`, `CloudTrial` and `Trusted Advisor`.

Hight light of the part
--
1. Module 7 introduction
2. Amazon CloudWatch
3. AWS CloudTrial
4. AWS Trusted Advisor
5. Module 7 summary
6. Module 7 quiz

Summary
--
The purpose of this module is to present tree AWS's component to manage a second part of the security : monitoring and analytics.

The first one, `AWS CloudWatch` is a web service that allow customers to monitor theirs environments and setup alarms from monitoring metrics.\
From the metrics collected by AWS, customer can create alarms that can perfom actions if the value is close or above a predefined threshold, as an example, alarms can be create to identify zombi ressources.\
The Cloud dashbord feature permit to acccess to all the metrics of an account from a single location.

CloudWatch |
| :---: 
| ![image](https://user-images.githubusercontent.com/79169883/137797701-a1d00425-83dc-4d21-96a2-6d2ebda127ef.png) | 
| ![image](https://user-images.githubusercontent.com/79169883/137797498-3ebb7e8d-abdd-4140-bff5-d41930295e02.png) | 


The second component, `AWS CloudTrail`, record all API calls for curtomer account, such as identity of the API caller, time stamp, source IP address.
An option, CloudTrail Insights, allow CloudTrial to automatically dectect unusual API activities in AWS customer account. As example, CloudTrail Insights might detect that a higher number of ressources was launched in customer account.
CloudTrail |
| :---: 
| ![image](https://user-images.githubusercontent.com/79169883/137800740-0e48428c-c2b3-4dd8-a018-701f97df98d9.png) | 
| ![image](https://user-images.githubusercontent.com/79169883/137800849-89304b9e-823d-4e2f-b95a-5f05667c25c5.png) | 


The last component of this module is a web service, `AWS Trusted Advisor`, that inspect customer AWS environment and compare its findings to AWS best practices in five categories and offer a list of recommanded actions :
* Cost optimization
* Performance
* Security
* Fault tolerance
* Service limits


AWS Trusted Advisor |
| :---: 
| ![image](https://user-images.githubusercontent.com/79169883/137801821-1a00eb71-b665-4283-900f-c26944180b0f.png) |
| ![image](https://user-images.githubusercontent.com/79169883/137801658-1e302468-bb94-4631-a7cd-93000d537933.png) | 


Quick notes
--
Just make a copy past of end additionnals ressources.\
I found them usefull.

* [Management and Governance on AWS](https://aws.amazon.com/products/management-tools "Management and Governance on AWS")
* [Monitoring and Observability](https://aws.amazon.com/products/management-tools/use-cases/monitoring-and-observability/ "Monitoring and Observability")
* [Configuration, Compliance, and Auditing](https://aws.amazon.com/products/management-tools/use-cases/configuration-compliance-and-auditing/ "Configuration, Compliance, and Auditing")
* [AWS Management & Governance Blog](https://aws.amazon.com/blogs/mt/ "AWS Management & Governance Blog")
* [Whitepaper: AWS Governance at Scale](https://docs.aws.amazon.com/whitepapers/latest/aws-governance-at-scale/introduction.html "Whitepaper: AWS Governance at Scale")

