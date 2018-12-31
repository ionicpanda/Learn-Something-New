Basic Terminology
1. Injection Point
  Where vulnerability exists
2. Vulnerability
  Flaw or weakness of the system
3. Payload
  Script or code used to identify vulnerability
4. Exploitation
  Taking advantage of vulnerability to gain system access. 
  
Information
1. site - nokia.com
2. subdomains - 
  Use virustotal.com to help find subdomains.
3. You need to sort the subdomains by unpopularity
    Find the less traveled road to get more bounties.
4. Find the IP addresses of the websites.
   ping domain name or ip address 
5. Which programming language is the website using? 
  Could use wappalyzer or site:domain.com .jsp etc...
  Use kali program, whatweb developer.com 
6. Gather open ports and services 
   nmap ip {normal scan} 
   aggressive scanning
   nmap ip -sV
   Detailed information about the target 
   nmap ip | nmap -sC ip 
7. Server information 
  iis | apache | tomcat | nginx
  whatweb any.com 
  
