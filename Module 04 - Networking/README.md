Module 4 - Networking
================


About
------------
This module is an introduction to AWS Networking connectivity.\
We learn that AWS Virtual Private Cloud is setup by design to bring security to customer hosted infrastructure.


Hight light of the part
--
1. Module 4 introduction
2. Connectivity to AWS
3. Subnets and network access control lists
4. Global networking
5. Module 4 summary
6. Module 4 quiz

Summary
--
I really appreciate the way security is design : security groups deny by default all incorming traffic, the customer must open requested port (the purpose is to lead the customer to not open `any` posts). Inside the VPC, Public and Private subnet traffic is secured by Network access control lists (ACLs). Internet Gateway, Virtual private Gateway, VPN or Direct Connect allow access to hosted ressources.\

VPC | Public subnet | Private Subnet |  Network ACLs
| :---: | :---: | :---: | :---:
| ![image](https://user-images.githubusercontent.com/79169883/132858867-74f24d46-ee14-492c-bd9c-103f319a9c00.png) | ![image](https://user-images.githubusercontent.com/79169883/132858914-d3e43005-fcbd-4d98-8171-e3df5e976b39.png) | ![image](https://user-images.githubusercontent.com/79169883/132858965-6d627048-2c03-46a3-83d9-22f783ec4c64.png) | ![image](https://user-images.githubusercontent.com/79169883/132859909-8501a2c1-5627-4618-83d4-17bf76c0ce69.png)
| | | |
**Internet Gateway** | **Virtual Private Gateway** | **VPN** | **Direct Connect**
| ![image](https://user-images.githubusercontent.com/79169883/132857924-de4da214-fb7f-48ae-8ee2-f8e33fea54b6.png) | ![image](https://user-images.githubusercontent.com/79169883/132857882-ede6828c-5156-45c9-91b6-a72949e4bc30.png) | ![image](https://user-images.githubusercontent.com/79169883/132859709-adfad097-7463-47b8-ab38-6a2c700dae80.png) | ![image](https://user-images.githubusercontent.com/79169883/132857826-8cf0fb94-56c5-41c4-8a65-967b370ce180.png)



Also, i discovers AWS DNS product : Route53. A part of this module introduce links between Route53 and CloudFront and EdgeLocation functionnality.\

Route 53 | CloudFront | Edge Location
| :---: | :---: | :---:
![image](https://user-images.githubusercontent.com/79169883/132855375-7d04b556-2814-4ef4-b459-3eda08a6fb16.png) | ![image](https://user-images.githubusercontent.com/79169883/132855309-32383808-3d02-45e2-9620-9f6ffe1851b0.png) | ![image](https://user-images.githubusercontent.com/79169883/132855233-4ec847e1-4cbf-413e-882d-6ac9b12d0ffe.png)

This module bring key to design web server hosting infrastructure\
![image](https://user-images.githubusercontent.com/79169883/132872606-26486039-b0d9-4f7c-ba43-ae8f254a08ab.png)

Or redundant hosted infrastrtuctures 
![image](https://user-images.githubusercontent.com/79169883/132872766-5ab9eece-1bee-4064-93fb-3240ca5910b3.png)

Quick notes
--
Just make a copy past of end additionnals ressources.\
I found them usefull.

* [Networking and Content Delivery on AWS](https://aws.amazon.com/fr/products/networking/ "Networking and Content Delivery on AWS")
* [AWS Networking & Content Delivery Blog](https://aws.amazon.com/fr/blogs/networking-and-content-delivery/ "AWS Networking & Content Delivery Blog")
* [Amazon Virtual Private Cloud](https://aws.amazon.com/fr/vpc/ "Amazon Virtual Private Cloud")
* [What is Amazon VPC?](https://docs.aws.amazon.com/vpc/latest/userguide/what-is-amazon-vpc.html "What is Amazon VPC?")
* [How Amazon VPC works](https://docs.aws.amazon.com/vpc/latest/userguide/how-it-works.html "How Amazon VPC works")
