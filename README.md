# InformationGathering
Information Gathering Techiques

# To perform information gathering techniques

# AIM:

To perform information gathering techniques using kali linux 

## STEPS:

### Step 1:

Install kali linux either in partition or virtual box or in live mode

### Step 2:

Investigate on the various categories of tools as follows:

### Step 3:
Open terminal/browser and try execute necessary commands/use url to perform information gathering

## Pen Test Tools Categories:
Following Categories of pen test tools are identified for information gathering:

Footprinting is a part of the reconnaissance process which is used for gathering possible information about a target computer system or network.

http://www.whois.com/whois website to get detailed information about a domain name information including its owner, its registrar, date of registration, expiry, name server, owner's contact information, etc.

## OUTPUT:
![lab2(1)](https://github.com/user-attachments/assets/6ee7fcc2-15e6-4228-b317-11817afd362d)
## Finding IP address:
ping command is available on Windows as well as on Linux OS. Following is the example to find out the IP address of youtube .com

## OUTPUT:
![lab2(2)](https://github.com/user-attachments/assets/27253a7b-4b4a-4f36-956d-227798f67a1d)

## Finding Hosting Company:
get further detail by using ip2location.com website.
## OUTPUT :
![lab2(3)](https://github.com/user-attachments/assets/b6c960dc-c7e4-4ec9-8658-efda2f1b125b)
## History of the website:
## OUTPUT :
![lab2(4)](https://github.com/user-attachments/assets/e4e12ae6-3543-4c00-920a-bc7f0174ae9c)
![lab2(5)](https://github.com/user-attachments/assets/c4d933a9-87b6-444f-b8ff-a4d08a2a5841)

## Webserver Fingerprinting:
## Netcat:
nc 172.17.52.118 80

## OUTPUT:
![lab2(6)](https://github.com/user-attachments/assets/6b791439-bf3a-4ae8-ad6f-7afcf1731e1e)

## nmap:

nmap -p 21 -sV --script=banner ftp.vim.org
## OUTPUT :
![lab2(7)](https://github.com/user-attachments/assets/8da40585-0baf-4a01-b24a-a6a0cf9d059f)

## Whatweb:
whatweb zoho.com
whatweb google.com
## OUTPUT:
![lab2(8)](https://github.com/user-attachments/assets/acc7bff5-f5d2-4631-8906-128fbcb8a48e)

## httprint:
httprint -h 172.17.52.201 -s /usr/share/httprint/signatures.txt -P0 |more
## OUTPUT :
![lab2(9)](https://github.com/user-attachments/assets/ab3f61a1-c3f7-4787-8c4a-cc92f2b65b9d)

## Tracing the Location:
## TCP Traceroute:
sudo traceroute -T www.instagram.com
## OUTPUT :
![lab2(10)](https://github.com/user-attachments/assets/f9d38703-0eae-42b6-b0b0-02a6b909fa6a)

## UDP Traceroute:
sudo traceroute -U www.instagram.com
## OUTPUT :
![lab2(11)](https://github.com/user-attachments/assets/8a4b99b0-e2ea-41a0-944e-3508707777ca)
## ICMP Traceroute:
sudo traceroute  www.facebook.com
## OUTPUT :
![lab2(12)](https://github.com/user-attachments/assets/85f3b2bb-ef9f-441e-8af3-85392624d266)
## RESULT:
The information gathering techniques tools/procedure were  identified successfully
