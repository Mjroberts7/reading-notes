Reading
Lessons Learned from the Capital One Data Breach (PDF)

1. What were the three commands used for the attack? Get Credentials, List Buckets, Download Files. 
2. What misconfiguration of AWS components allowed the attacker to access sensitive data? the firewall was misconfigured. Specifically the WAF through the command "http://169.254.169.254/iam/security-credentials command". 
3. What are two of the AWS Governance practices that could have prevented such attack? Review all access paths and permissions from human identities or non-human identities to data storages. The second governance that shouldve been implemented is verification of the use of version 2 on EC2 Metadata instead of version 1. 

i got info from these sites
- [Lessons Learned from the Capital One Data Breach (PDF)](chrome-extension://efaidnbmnnnibpcajpcglclefindmkaj/https://www.zscaler.com/resources/white-papers/capital-one-data-breach.pdf)

## Things I want to know more about