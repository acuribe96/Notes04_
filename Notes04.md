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

*Account root user*

- full access to all resources
- recommended to not use a day-to-day basis

* Securing a new AWS account*

- Step 1: stop using the account root user
- Step 2: enable MFA
- Step 3: use AWS CloudTrail (tracks user activity on your account)
- Step 4: enable a billing report such as AWS Cost and Usage Report

*AWS Organization*

- allows multiple AWS accounts

*SCPs (service control policies)*

- ensures that accounts comply with access control guidelines
- offer centralized control over accounts

*AWS KWS (key management service)*

- enables you to create and manage encryption keys

  *AWS Shield*

  - managed distributed denial of service (DDoS) protection service
  - safeguards running applications
  - minimize application downtime and latency

*Encryption*

- encodes data with a secret key, which makes it unreadable
 
  *Encryption data at rest*

  - data store physically

  *Encryption data in transit*

  - data moving across a network
 
  *Compliance programs*

  - certifications and attestations
  - laws, regulation, and policy
  - alignments and frameworks

  *AWS Config*

  - assess, audit, and evaluate the configurations of AWS resources

 *AWS Artifact*

 - resource for compliance-related information


**Question 2**

> Even if an attacker gains access to your data they cannot make sense of it.

- Goes to show how much security Amazon implents and protects their customers.

> Out of the box access is no access until you explicity allow it via a policy

- As said earlier Amazon implents great security and is strict on rules. If a policy wasn't made by the controller, no user can access it.

**Question 4**
- Will Amazon ever have full control of your system in an EC2?
