Aneissa Uribe
CIT114 - Note04

**AWS Cloud Security**

*Share responsibility*

- customers are responsible for security 'in' the cloud
- Amazon is responsible for security 'of' the cloud

*Customer responsibility*

- Amazon EC2
- Application
- Security groups
- Network
- Account management

*IaaS (Infrastructure as a Service)

- more flexibility in networking and storage settings
- responsible for managing more aspects of security
- configures the access controls

*PaaS (Platform as a Service)

- does not need to manage the underlying infrastructure
- handles the opertating system, database patching, firewall configuration, and disaster recovery
- focus on managing code or data

*SaaS (Software as a Service)

- centrally hosted
- pay-as-you-go basis
- customers do not need to manage the infrastructure that supports the service

*IAM (Indentity Access Managment)*

- manage access to AWS resources
- no-cost

*IAM user*

- person or application that can aunthenticate with an AWS account

*IAM group*

- collection of IAM users

*IAM Policy*

- document that defines which resources can be accessed and the level of access to each resource
- written in JSON files

*IAM Role*

- mechanism to grant a set of permissions for making AWS service request

*Type of access*

- programmic access (access key ID)
- management console access (12-digit account ID, MFA)

*MFA (multi-factor authentication)*

- provides increased security by requring a unique authentication code

*Identity based policies*

- attach a policy to any IAM entity

*Resourced-based policy*

- attached to a resource

*


**Question 2**

> Even if an attacker gains access to your data they cannot make sense of it.

-

> Out of the box access is no access until you explicity allow it via a policy

-

**Question 4**
- Will Amazon ever have full control of your system in an EC2?
