# Enumeration
Enumeration Techniques

## DATE: 15.03.2025

# Explore Google hacking and enumeration 

# AIM:

To use Google for gathering information and perform enumeration of targets

## STEPS:

### Step 1:

Install kali linux either in partition or virtual box or in live mode

### Step 2:

Investigate on the various Google hacking keywords and enumeration tools as follows:


### Step 3:
Open terminal and try execute some kali linux commands

## Pen Test Tools Categories:  

Following Categories of pen test tools are identified:
Information Gathering.

Google Hacking:

Google hacking, also known as Google dorking, is a technique that involves using advanced operators to perform targeted searches on Google. These operators can be used to search for specific types of information, such as sensitive data that may have been inadvertently exposed on the web. Here are some advanced operators that can be used for Google hacking:

site: This operator allows you to search for pages that are within a specific website or domain. For example, "site:example.com" would search for pages that are on the example.com domain.
Following searches for all the sites that is in the domain yahoo.com

filetype: This operator allows you to search for files of a specific type. For example, "filetype:pdf" would search for all PDF files.
Following searches for pdf file in the domain yahoo.com



intext: This operator allows you to search for pages that contain specific text within the body of the page. For example, "intext:password" would search for pages that contain the word "password" within the body of the page.


inurl: This operator allows you to search for pages that contain specific text within the URL. For example, "inurl:admin" would search for pages that contain the word "admin" within the URL.

intitle: This operator allows you to search for pages that contain specific text within the title tag. For example, "intitle:index of" would search for pages that contain "index of" within the title tag.

link: This operator allows you to search for pages that link to a specific URL. For example, "link:example.com" would search for pages that link to the example.com domain.

cache: This operator allows you to view the cached version of a page. For example, "cache:example.com" would show the cached version of the example.com website.

 
# DNS Enumeration
## DNS Recon
provides the ability to perform:
Check all NS records for zone transfers
Enumerate general DNS records for a given domain (MX, SOA, NS, A, AAAA, SPF , TXT)
Perform common SRV Record Enumeration
Top level domain expansion

## dnsenum
Dnsenum is a multithreaded perl script to enumerate DNS information of a domain and to discover non-contiguous ip blocks. The main purpose of Dnsenum is to gather as much information as possible about a domain. The program currently performs the following operations:

Get the host’s addresses (A record).
Get the namservers (threaded).
Get the MX record (threaded).
Perform axfr queries on nameservers and get BIND versions(threaded).
Get extra names and subdomains via google scraping (google query = “allinurl: -www site:domain”).
Brute force subdomains from file, can also perform recursion on subdomain that have NS records (all threaded).
Calculate C class domain network ranges and perform whois queries on them (threaded).
Perform reverse lookups on netranges (C class or/and whois netranges) (threaded).
Write to domain_ips.txt file ip-blocks.
This program is useful for pentesters, ethical hackers and forensics experts. It also can be used for security tests.


## smtp-user-enum
Username guessing tool primarily for use against the default Solaris SMTP service. Can use either EXPN, VRFY or RCPT TO.
In metasploit list all the usernames using head /etc/passwd or cat /etc/passwd
select any username in the first column of the above file and check the same

## Telnet for smtp enumeration
Telnet allows to connect to remote host based on the port no. For smtp port no is 25
telnet <host address> 25 to connect
and issue appropriate commands

## nmap –script smtp-enum-users.nse <hostname>

The smtp-enum-users.nse script attempts to enumerate the users on a SMTP server by issuing the VRFY, EXPN or RCPT TO commands. The goal of this script is to discover all the user accounts in the remote system.

## OUTPUT:

# site:example.com
![image](https://github.com/user-attachments/assets/cf9ef203-22ff-4667-9f40-e3dda5778b3b)

## filetype:pdf
![image](https://github.com/user-attachments/assets/094048a2-dce5-4c36-9a98-743ffb25391a)

## intext:password
![image](https://github.com/user-attachments/assets/6865cada-088c-40bb-80db-7ba426e83474)

## inurl:admin
![image](https://github.com/user-attachments/assets/6c8d21f4-d798-44ae-a795-31b272050bd3)

## intitle:index of
![image](https://github.com/user-attachments/assets/7862bfbe-34e3-4b62-bb4f-90532310703a)

## link:example.com
![image](https://github.com/user-attachments/assets/626d151e-86c7-49b2-9542-24bd1d9633c3)

## cache:example.com
![image](https://github.com/user-attachments/assets/ba51f801-2a25-4015-b5e0-18fe0754fee8)

# DNS Enmueration

## DNS Recon
![image](https://github.com/user-attachments/assets/3b57fe81-0efb-459f-bb77-27b9ca1ad2f8)

## dnsenum
![image](https://github.com/user-attachments/assets/bc841a0e-d696-46bb-89d1-b98db9a993da)

## smtp-user-enum
![image](https://github.com/user-attachments/assets/f9c8acc9-5e57-4691-a72a-0da9a6e27327)
![image](https://github.com/user-attachments/assets/4f163cc4-8f35-4f89-9de6-77f22a5fa3f4)

## Telnet for smpt enumeration
![image](https://github.com/user-attachments/assets/50a6499b-e558-450b-86b6-8f124bf88903)

## nmap-script smtp-enum-user.nse
![image](https://github.com/user-attachments/assets/bc17fe39-c8e1-4f07-bcb7-3c70c0e11647)

## RESULT:
The Google hacking keywords and enumeration tools were identified and executed successfully

