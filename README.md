# Enumeration
Enumeration Techniques

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

## OUTPUT:
![image](https://github.com/subalakshmivenkat/Enumeration/assets/119393477/8e5e71a5-2e48-44ae-ba8a-417e93066393)

filetype: This operator allows you to search for files of a specific type. For example, "filetype:pdf" would search for all PDF files.
Following searches for pdf file in the domain yahoo.com

## OUTPUT:
![image](https://github.com/subalakshmivenkat/Enumeration/assets/119393477/a5ccc616-135a-4b88-9f13-7816b020a550)

intext: This operator allows you to search for pages that contain specific text within the body of the page. For example, "intext:password" would search for pages that contain the word "password" within the body of the page.


inurl: This operator allows you to search for pages that contain specific text within the URL. For example, "inurl:admin" would search for pages that contain the word "admin" within the URL.

## OUTPUT:
![239720312-61b83322-2aba-44f3-9a90-dc9bb3fe6175](https://github.com/subalakshmivenkat/Enumeration/assets/119393477/d1e7a2da-2455-4236-a3f6-ca1838840377)

intitle: This operator allows you to search for pages that contain specific text within the title tag. For example, "intitle:index of" would search for pages that contain "index of" within the title tag.

link: This operator allows you to search for pages that link to a specific URL. For example, "link:example.com" would search for pages that link to the example.com domain.

## OUTPUT:
![239720329-bf1840b8-075d-497e-8f1c-4ca6d8327982](https://github.com/subalakshmivenkat/Enumeration/assets/119393477/541d6242-40d8-4b38-9c66-b24dd9de2557)

cache: This operator allows you to view the cached version of a page. For example, "cache:example.com" would show the cached version of the example.com website.

## OUTPUT:
![239720337-e127c95b-a133-42d4-aa3d-a833faa3aad0](https://github.com/subalakshmivenkat/Enumeration/assets/119393477/a77c80e6-b035-4668-8b1d-c330bd055b4b)

# DNS Enumeration


## DNS Recon
provides the ability to perform:
Check all NS records for zone transfers
Enumerate general DNS records for a given domain (MX, SOA, NS, A, AAAA, SPF , TXT)
Perform common SRV Record Enumeration
Top level domain expansion
## OUTPUT:

![241196881-e27b6257-4d38-4365-a04f-6bd71610632a](https://github.com/subalakshmivenkat/Enumeration/assets/119393477/8b3ce664-c9c1-45f8-bc42-75414545defe)

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

![241198023-795c489d-ba57-4e77-9791-49c71fc3f4d3](https://github.com/subalakshmivenkat/Enumeration/assets/119393477/9cce2195-0702-4c29-8b72-c0d904bc668d)

## smtp-user-enum
Username guessing tool primarily for use against the default Solaris SMTP service. Can use either EXPN, VRFY or RCPT TO
In metasploit list all the usernames using head /etc/passwd or cat /etc/passwd:
select any username in the first column of the above file and check the same

![241410635-c41be6f0-d0d4-40eb-9074-136cabe5c74b](https://github.com/subalakshmivenkat/Enumeration/assets/119393477/e023646d-5d2c-456f-89f3-30905ccd6c36)

## Telnet for smtp enumeration
Telnet allows to connect to remote host based on the port no. For smtp port no is 25
telnet <host address> 25 to connect
and issue appropriate commands

![241409971-4fd9ca59-abdf-43bc-917c-71e2c7e4351d](https://github.com/subalakshmivenkat/Enumeration/assets/119393477/740b77a0-ddde-4533-a9bf-3c145f9e4241)


## nmap –script smtp-enum-users.nse 
The smtp-enum-users.nse script attempts to enumerate the users on a SMTP server by issuing the VRFY, EXPN or RCPT TO commands. The goal of this script is to discover all the user accounts in the remote system.
![241410190-9ca27cef-c123-4ab2-b4b1-13e67d6e6d19](https://github.com/subalakshmivenkat/Enumeration/assets/119393477/50937c76-80ab-446e-b186-1ac848c71c0b)


## RESULT:
The Google hacking keywords and enumeration tools were identified and executed successfully

