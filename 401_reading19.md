# Mj's Reading Notes

## Reading notes 19

1. What are some of the IoCs that GuardDuty can detect? Escalation of privileges, use of exposed credentials, or communication with malicious IP addresses, domains, presence of malware on Amazon EC2 instances and container workloads, or discovery of unusual patterns of login events on your database.
2. What are some of the data sources which GuardDuty can use? AWS CloudTrail management events, AWS CloudTrail event logs, VPC flow logs (from Amazon EC2 instances), and DNS logs.
3. How does GuardDuty use access behavior to spot potential malicious activity? Detecting things like instances deployed in a Region that hasn't been used before, or unusual API calls like a password policy change to reduce password strength.

Documentation 
- [What is Amazon GuardDuty?](https://docs.aws.amazon.com/guardduty/latest/ug/what-is-guardduty.html)
- [AWS re:Inforce 2019: Threat Detection on AWS: An Introduction to Amazon GuardDuty (FND216)](https://www.youtube.com/watch?v=czsuZXQvD8E)