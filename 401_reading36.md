# Mj's Reading Notes

## Reading Notes


1. Explain how a cross-site scripting attack works in non-technical terms. Cross site scripting is basically when a person logs in to a website and a hacker is able to gain access to the website through the credentials of the original user. 
2. What are the three types of XSS attacks?
    - Reflected XSS -  malicious script comes from the current HTTP request.
    - Stored XSS - malicious script comes from the website's database.
    - DOM-Based XSS - vulnerability exists in client-side code rather than server-side code.
3. If an attacker successfully exploits a XSS vulnerability, what malicious actions would they be able to perform?
What are some security controls that can be implemented to prevent XSS attacks? They would be able to do anything that the original customer would be able to perform. Filtering input on arrival is a strong security goal against XSS. using appropriate headers. Encoding Data on output is another strong security controls.


Documentation
- [Cross-site scripting](https://portswigger.net/web-security/cross-site-scripting)
- [Security Report for In-Production Web Applications](chrome-extension://efaidnbmnnnibpcajpcglclefindmkaj/https://www.rapid7.com/globalassets/_pdfs/whitepaperguide/rapid7-tcell-application-security-report.pdf)