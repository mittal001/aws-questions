###### 1. 

What are the DHCP option attributes used to assign private DNS servers to your VPC?

- [ ] A. dns resolution and domain name
- [ ] B. hostnames and internet domain
- [ ] C. domain servers and domain name
- [ ] D. domain-name-servers and domain-name

<details  hid="3ddd8208-c7ec-49ce-8fc2-0b93639ac1b2">
  <summary>Answer</summary>
  D
  <br />
  Knowledge Area: Virtual Private Cloud (VPC)
</details>

---


###### 2. 

What are two features of CloudWatch operation?

- [ ] A. CloudWatch does not support custom metrics
- [ ] B. CloudWatch permissions are granted per feature and not AWS resource
- [ ] C. collect and monitor operating system and application generated log files
- [ ] D. AWS services automatically create logs for CloudWatch
- [ ] E. CloudTrail generates logs automatically when AWS account is activated

<details>
  <summary>Answer</summary>
  B, C
  <br />
  Knowledge Area: Monitoring Services
</details>

---

###### 3. 

You have an application that collects monitoring data from 10,000 sensors (IoT) deployed in the USA. The datapoints are comprised of video events for home security and environment status alerts. The application will be deployed to AWS with EC2 instances as data collectors. What AWS storage service is preferred for storing video files from sensors?

- [ ] A. RedShift
- [ ] B. RDS
- [ ] C. S3
- [ ] D. DynamoDB

<details>
  <summary>Answer</summary>
  C
  <br />
  Knowledge Area: Storage Services
</details>

---


###### 4. 

What storage type enable permanent attachment of volumes to EC2 instances?

- [ ] A. S3
- [ ] B. RDS
- [ ] C. TDS
- [ ] D. EBS
- [ ] E. instance store

<details>
  <summary>Answer</summary>
  D
  <br />
  Knowledge Area: EC2 Compute
</details>

---


###### 5. 

What are two advantages of selecting default tenancy option for your VPC when creating it?

- [ ] A. performance and reliability
- [ ] B. some AWS services do not work with a dedicated tenancy VPC
- [ ] C. tenant can launch instances within VPC as default or dedicated instances
- [ ] D. instance launch is faster

<details>
  <summary>Answer</summary>
  B,C
  <br />
  Knowledge Area: Virtual Private Cloud (VPC)
</details>

---


###### 6. 

What two statements correctly describe Amazon virtual private gateway?

- [ ] A. assign to private subnets only
- [ ] B. assign to public subnets only
- [ ] C. single virtual private gateway per VPC
- [ ] D. multiple virtual private gateways per VPC
- [ ] E. single virtual private gateway per region

<details>
  <summary>Answer</summary>
  A,C
  <br />
  Knowledge Area: Virtual Private Cloud (VPC)
</details>

---


###### 7. 

What are two features that correctly describe Availability Zone (AZ) architecture?

- [ ] A. multiple regions per AZ
- [ ] B. interconnected with private WAN links
- [ ] C. multiple AZ per region
- [ ] D. interconnected with public WAN links
- [ ] E. data auto-replicated between zones in different regions
- [ ] 6. Direct Connect supports Layer 2 connectivity to region

<details>
  <summary>Answer</summary>
  B,C
  <br />
  Knowledge Area: Fault Tolerant Systems
</details>

---


###### 8. 

What AWS services encrypts data at rest by default? (Select two)

- [ ] A. S3
- [ ] B. AWS Storage Gateway
- [ ] C. EBS
- [ ] D. Glacier
- [ ] E. RDS

<details>
  <summary>Answer</summary>
  B,D
  <br />
  Knowledge Area: Storage Services
</details>

---


###### 9. 

What two attributes are only associated with CloudFront private content?

- [ ] A. Amazon S3 URL
- [ ] B. signed cookies
- [ ] C. web distribution
- [ ] D. signed URL
- [ ] E. object

<details>
  <summary>Answer</summary>
  B,D
  <br />
  Knowledge Area: Deployment
</details>

---


###### 10. 

What two statements correctly describe how to add or modify IAM roles to a running EC2 instance?

- [ ] A. attach an IAM role to an existing EC2 instance from the EC2 console
- [ ] B. replace an IAM role attached to an existing EC2 instance from the EC2 console
- [ ] C. attach an IAM role to the user account and relaunch the EC2 instance
- [ ] D. add the EC2 instance to a group where the role is a member

<details>
  <summary>Answer</summary>
  A,B
  <br />
  Knowledge Area: EC2 Compute
</details>

---


###### 11. 

What are the minimum components required to enable a web-based application with public web servers and a private database tier? (select three)

- [ ] A. Internet gateway
- [ ] B. Assign EIP addressing to database instances on private subnet
- [ ] C. Virtual private gateway
- [ ] D. Assign database instances to private subnet and private IP addressing
- [ ] E. Assign EIP and private IP addressing to web servers on public subnet

<details>
  <summary>Answer</summary>
  A,D,E
  <br />
  Knowledge Area: Virtual Private Cloud (VPC)
</details>

---


###### 12. 

What two statements accurately describe Amazon VPC architecture?

- [ ] A. Elastic Load Balancer (ELB) cannot span multiple availability zones
- [ ] B. VPC does not support DMVPN connection
- [ ] C. VPC subnet cannot span multiple availability zones
- [ ] D. VPC cannot span multiple regions
- [ ] E. Flow logs are not supported within a VPC

<details>
  <summary>Answer</summary>
  C,D
  <br />
  Knowledge Area: Virtual Private Cloud (VPC)
</details>

---


###### 13. 

What feature enables CloudWatch to manage capacity dynamically for EC2 instances?

- [ ] A. replication lag
- [ ] B. Auto-Scaling
- [ ] C. Elastic Load Balancer
- [ ] D. vertical scaling

<details>
  <summary>Answer</summary>
  B
  <br /> 
  Knowledge Area: Monitoring Services
</details>

---


###### 14. 

What authentication method provides Federated Single Sign-On (SSO) for cloud applications?

- [ ] A. ADS
- [ ] B. ISE
- [ ] C. RADIUS
- [ ] D. TACACS
- [ ] E. SAML

<details>
  <summary>Answer</summary>
  E
  <br /> 
  Knowledge Area: Security Architecture
</details>

---


###### 15. 

What method detects when to replace an EC2 instance that is assigned to an Auto-Scaling group?

- [ ] A. health check
- [ ] B. load balancing algorithm
- [ ] C. EC2 health check
- [ ] D. not currently supported
- [ ] E. dynamic path detection
- [ ] 6. Auto-Scaling

<details>
  <summary>Answer</summary>
  A
  <br /> 
  Knowledge Area: EC2 Compute
</details>

---


###### 16. 

What two resource tags are supported for an EC2 instance?

- [ ] A. VPC endpoint
- [ ] B. EIP
- [ ] C. network interface
- [ ] D. security group
- [ ] E. Flow Log

<details>
  <summary>Answer</summary>
  A,E
  <br />
  Knowledge Area: EC2 Compute
</details>

---


###### 17. 

How is a volume selected (identified) when making an EBS Snapshot?

- [ ] A. account id
- [ ] B. volume id
- [ ] C. tag
- [ ] D. ARN

<details>
  <summary>Answer</summary>
  D
  <br /> 
  Knowledge Area: Deployment
</details>

---


###### 18. 

What two features provide an encrypted (VPN) connection from VPC to an enterprise data center?

- [ ] A. Internet gateway
- [ ] B. Amazon RDS
- [ ] C. Virtual private gateway
- [ ] D. CSR 1000V router
- [ ] E. NAT gateway

<details>
  <summary>Answer</summary>
  C,D
  <br />
  Knowledge Area: Virtual Private Cloud (VPC)
</details>

---


###### 19. 

What are two advantages of cross-region replication of an S3 bucket?

- [ ] A. cost
- [ ] B. security compliance
- [ ] C. scalability
- [ ] D. Beanstalk support
- [ ] E. minimize latency

<details>
  <summary>Answer</summary>
  B,E
  <br />
  Knowledge Area: Storage Services
</details>

---


###### 20. 

What consistency model is the default used by DynamoDB?

- [ ] A. strongly consistent
- [ ] B. eventually consistent
- [ ] C. no default model
- [ ] D. casual consistency
- [ ] E. sequential consistency

<details>
  <summary>Answer</summary>
  B
  <br /> 
  Knowledge Area: Database Services
</details>

---


###### 21. 

What features are required to prevent users from bypassing AWS CloudFront security? (Select three)

- [ ] A. Bastion host
- [ ] B. signed URL
- [ ] C. IP whitelist
- [ ] D. signed cookies
- [ ] E. origin access identity (OAI)

<details>
  <summary>Answer</summary>
  B,D,E
  <br />
  Knowledge Area: Security Architecture
</details>

---


###### 22. 

What are the advantages of NAT gateway over NAT instance? (Select two)

- [ ] A. NAT gateway requires a single EC2 instance
- [ ] B. NAT gateway is scalable
- [ ] C. NAT gateway translates faster
- [ ] D. NAT gateways is a managed service
- [ ] E. NAT gateway is Linux-based

<details>
  <summary>Answer</summary>
  B,D
  <br />
  Knowledge Area: Virtual Private Cloud (VPC)
</details>

---


###### 23. 

What two fault tolerant features does Amazon RDS support?

- [ ] A. copy snapshot to a different region
- [ ] B. create read replica to a different region
- [ ] C. copy unencrypted read-replica only
- [ ] D. copy read/write replica and snapshot

<details>
  <summary>Answer</summary>
  A,B
  <br />
  Knowledge Area: Database Services
</details>

---


###### 24. 

What two features describe an Application Load Balancer (ALB)?

- [ ] A. dynamic port mapping
- [ ] B. SSL listener
- [ ] C. layer 7 load balancer
- [ ] D. backend server authentication
- [ ] E. multi-region forwarding

<details>
  <summary>Answer</summary>
  A,C
  <br />
  Knowledge Area: Fault Tolerant Systems
</details>

---


###### 25. 

You have configured a security group to allow ICMP, SSH and RDP inbound and assigned the security group to all instances in a subnet. There is no access to any Linux-based or Windows-based instances and you cannot Ping any instances. The network ACL for the subnet is configured to allow all inbound traffic to the subnet. What is the most probable cause?

- [ ] A. on-premises firewall rules
- [ ] B. security group and network ACL outbound rules
- [ ] C. network ACL outbound rules
- [ ] D. security group outbound rules
- [ ] E. Bastion host required

<details>
  <summary>Answer</summary>
  C
  <br /> 
  Knowledge Area: Security Architecture
</details>

---


###### 26. 

You have been asked to setup a VPC endpoint connection between VPC and S3 buckets for storing backups and snapshots. What AWS components are currently required when configuring a VPC endpoint?

- [ ] A. Internet gateway
- [ ] B. NAT instance
- [ ] C. Elastic IP
- [ ] D. private IP address

<details>
  <summary>Answer</summary>
  D
  <br /> 
  Knowledge Area: Virtual Private Cloud (VPC)
</details>

---


###### 27. 

What three attributes are used to define a launch configuration template for an Auto-Scaling group?

- [ ] A. instance type
- [ ] B. private IP address
- [ ] C. Elastic IP
- [ ] D. security group
- [ ] E. AMI

<details>
  <summary>Answer</summary>
  A,D,E
  <br />
  Knowledge Area: EC2 Compute
</details>

---


###### 28. 

You have enabled Amazon RDS database services in VPC1 for an application that has public web servers in VPC2. How do you connect the web servers to the RDS database instance so they can communicate considering the VPC's are in the same region?

- [ ] A. VPC endpoints
- [ ] B. VPN gateway
- [ ] C. path-based routing
- [ ] D. VPC peering
- [ ] E. AWS Network Load Balancer

<details>
  <summary>Answer</summary>
  D
  <br /> 
  Knowledge Area: Virtual Private Cloud (VPC)
</details>

---


###### 29. 

What two methods are recommended by AWS for protecting EBS data at rest?

- [ ] A. replication
- [ ] B. snapshots
- [ ] C. encryption
- [ ] D. VPN

<details>
  <summary>Answer</summary>
  B,C
  <br />
  Knowledge Area: Fault Tolerant Systems
</details>

---


###### 30. 

What security problem is solved by using Cross-Origin Resource Sharing (CORS)?

- [ ] A. enable HTTP requests from within scripts to a different domain
- [ ] B. enable sharing of web-based files between different buckets
- [ ] C. provide security for third party objects within AWS
- [ ] D. permits sharing objects between AWS services

<details>
  <summary>Answer</summary>
  A
  <br /> 
  Knowledge Area: Storage Services
</details>

---


###### 31. 

What two features are enabled with S3 services?

- [ ] A. store objects of any size
- [ ] B. dynamic web content
- [ ] C. supports Provisioned IOPS
- [ ] D. store virtually unlimited amounts of data
- [ ] E. bucket names are globally unique

<details>
  <summary>Answer</summary>
  D,E
  <br />
  Knowledge Area: Storage Services
</details>

---


###### 32. 

What is the purpose of a local route within a VPC route table?

- [ ] A. local route is derived from the default VPC CIDR block 10.0.0.0/16
- [ ] B. communicate between instances within the same subnet or different subnets
- [ ] C. used to communicate between instances within the same subnet
- [ ] D. default route for communicating between private and public subnets
- [ ] E. only installed in the main route table

<details>
  <summary>Answer</summary>
  C
  <br /> 
  Knowledge Area: Virtual Private Cloud (VPC)
</details>

---


###### 33. 

What feature is supported when attaching or detaching an EBS volume from an EC2 instance?

- [ ] A. EBS volume can be attached and detached to an EC2 instance in the same region
- [ ] B. EBS volume can be attached and detached to an EC2 instance that is cross-region
- [ ] C. EBS volume can only be copied and attached to an EC2 instance that is cross-region
- D. EBS volume can only be attached and detached to an EC2 instance in the same Availability Zone

<details>
  <summary>Answer</summary>
  D
  <br />
  Knowledge Area: EC2 Compute
</details>

---


###### 34. 

What Amazon AWS service supports real-time processing of data stream from multiple consumers and replay of records?

- [ ] A. DynamoDB
- [ ] B. EMR
- [ ] C. Kinesis data streams
- [ ] D. SQS
- E. RedShift

<details>
  <summary>Answer</summary>
  C
  <br /> 
  Knowledge Area: Deployment
</details>

---


###### 35. 

What is the fastest and easiest method for migrating an on-premises VMware virtual machine to the AWS cloud?

- [ ] A. Amazon Marketplace
- [ ] B. AWS Server Migration Service
- [ ] C. AWS Storage Gateway
- [ ] D. EC2 Import/Export

<details>
  <summary>Answer</summary>
  B
  <br /> 
  Knowledge Area: Deployment
</details>

---


###### 36. 

What class of EC2 instance type is recommended for database servers?

- [ ] A. memory optimized
- [ ] B. compute optimized
- [ ] C. storage optimized
- [ ] D. general purpose optimized

<details>
  <summary>Answer</summary>
  A
  <br /> 
  Knowledge Area: EC2 Compute
</details>

---


###### 37. 

What encryption support is available for tenants that are deploying AWS DynamoDB?

- [ ] A. server-side encryption
- [ ] B. client-side encryption
- [ ] C. client-side and server-side encryption
- [ ] D. encryption not supported
- [ ] E. block level encryption

<details>
  <summary>Answer</summary>
  B
  <br /> 
  Knowledge Area: Database Services
</details>

---


###### 38. 

What are two characteristics of an Amazon security group?

- [ ] A. instance level packet filtering
- [ ] B. deny rules only
- [ ] C. permit rules only
- [ ] D. subnet level packet filtering
- [ ] E. inbound only

<details>
  <summary>Answer</summary>
  A,C
  <br />
  Knowledge Area: Virtual Private Cloud (VPC)
</details>

---


###### 39. 

How is Route 53 configured for Warm Standby fault tolerance? (Select two)

- [ ] A. automated health checks
- [ ] B. path-based routing
- [ ] C. failover records
- [ ] D. Alias records

<details>
  <summary>Answer</summary>
  A,C
  <br />
  Knowledge Area: Fault Tolerant Systems
</details>

---


###### 40. 

What is the difference between Stream-based and AWS Services when enabling Lambda?

- [ ] A. streams maintains event source mapping in Lambda
- [ ] B. streams maintains event source mapping in event source
- [ ] C. streams maintains event source mapping in EC2 instance
- [ ] D. streams maintains event source mapping in notification
- [ ] E. streams maintains event source mapping in API

<details>
  <summary>Answer</summary>
  A
  <br /> 
  Knowledge Area: Deployment
</details>

---
