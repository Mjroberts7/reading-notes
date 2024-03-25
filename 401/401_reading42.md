# Mj's Reading Notes 

## Reading Notes 42

1. Name the six credential-gathering techniques which Mimikatz is able to perform and explain how two of them work.
    - pass-the-hash: Attackers leverage Mimikatz to utilize hash strings for logging into target computers without needing to crack passwords, akin to having a master key to access all doors in a building.
    - pass-the-ticket: Newer versions of Windows store password data in tickets, and Mimikatz enables users to pass Kerberos tickets to log into another computer, just like the pass-the-hash technique but with tokens.
    - Overpass-the-hash(pass-the-key): The technique passes a unique key obtained from a domain controller to impersonate a user.
    - Kerberoast golden tickets: This is a pass-the-ticket attack, but it’s a specific ticket for a hidden account called KRBTGT, which is the account that encrypts all of the other tickets. A golden ticket provides you with non-expiring domain admin credentials to any computer on the network.
    - Kerberoast silver tickets: Another pass-the-ticket, but a silver ticket takes advantage of a feature in Windows that makes it easy for you to use services on the network. Kerberos grants a user a ticket-granting server (TGS) ticket, and a user can use that ticket to authentic to service accounts on the network. Microsoft doesn’t always check a TGS after it’s issued, so it’s easy to slip past any safeguards. 
    - pass-the-cache: Finally an attack that doesn’t take advantage of Windows! A pass-the-cache attack is generally the same as a pass-the-ticket, but this one uses the saved and encrypted login data on a Mac/UNIX/Linux system.
2. What are four ways we can defend against Mimikatz attacks. Explain how two of the mitigations can stop Mimikatz.
    - Restrict admin privileges: This can be done by limiting admin privileges to only users who need them.
    - Disable password-caching: change your default settings to cache zero recent passwords. This can be accessed through Windows Settings > Local Policy > Security Options > Interactive Logon.  
    - Turn off debug privileges: Turning off debugging privileges on machines is a best practice to safeguard your system.  
    - Configure additional local security authority (LSA) protection: Upgrading to Windows 10 can help mitigate the types of authentication attacks that Mimikatz enables. However, when this isn’t possible, Microsoft has additional LSA configuration items that help reduce the attack surface area. 

---
Documentation 
- [What is Mimikatz?](https://www.varonis.com/blog/what-is-mimikatz)