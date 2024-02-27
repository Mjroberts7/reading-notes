# Mj's Reading Notes 

## Reading notes 37


1. What is the main goal of Threat Hunting and how is it different from traditional threat monitoring? Threat hunting is actively searching for indicators of compromise to detect any breaches. Threat monitoring is no proactively searching your systems but monitoring and keeping an eye on your systems so you will be aware if a breach or attempt is made. 
2. What are the four types of YARA rules and what does each one of them use to identify and classify malicious software? 
    - string-based rules - use strings of text as values to detect malware.
    - file metadata-based rules - use metadata about files being analyzed to identify malware. 
    - hash-based rules - use cryptographic hashes to identify malware.
    - network-based rules - use network traffic data to identify malware.
3. How are YARA rules similar to how Anti-Virus programs detect malicious software? They use pre-determined criteria, then use search the data and anything that matches the criteria is flagged. 

Documentation
- [What Are YARA Rules?](https://archerint.com/what-are-yara-rules/)
- [Threat Hunting using YARA](https://www.geeksforgeeks.org/threat-hunting-using-yara/)
- [YARA Rules GitHub Project](https://github.com/Yara-Rules/rules)
    - This project covers the need of a group of IT Security Researchers to have a single repository where different Yara signatures are compiled, classified and kept as up to date as possible, and began as an open source community for collecting Yara rules.