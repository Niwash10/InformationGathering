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

<img width="1880" height="907" alt="image" src="https://github.com/user-attachments/assets/2b02e199-eaa9-45b1-9242-b89290b73d8e" />


## Finding IP address:
ping command is available on Windows as well as on Linux OS. Following is the example to find out the IP address of facebook.com.

## output

<img width="1917" height="413" alt="image" src="https://github.com/user-attachments/assets/0fd62d0d-5591-46c6-b0f0-ac9bf321ac2a" />


## Finding Hosting Company
get further detail by using ip2location.com website.
## output

<img width="1916" height="745" alt="image" src="https://github.com/user-attachments/assets/345897e9-d4f7-4600-b4e0-6ab58338c7f8" />



## History of the website:

## output
https://web.archive.org/

<img width="1912" height="922" alt="image" src="https://github.com/user-attachments/assets/ff35e0bf-47f8-4c48-b3a0-0b7460575e0f" />


# Webserver Fingerprinting:

## Netcat:
```
GET / HTTP/1.1
Host: example.com
```
<img width="1908" height="670" alt="image" src="https://github.com/user-attachments/assets/479f76bd-0cd7-4417-a275-a53bdea9c6fa" />




## nmap:

## output
<img width="1095" height="161" alt="image" src="https://github.com/user-attachments/assets/3e5939b5-2f73-448b-b837-a2380edf2793" />


## Whatweb
### output
<img width="1905" height="170" alt="image" src="https://github.com/user-attachments/assets/7ec52b4f-4dd8-47f1-8127-b70c6a9f8ea4" />


## httprint
### output
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/847fd97c-93d8-4ae2-89c6-cbf4862d9589" />




# Tracing the Location
TCP Traceroute:
sudo traceroute -T www.google.com
## output
<img width="911" height="322" alt="image" src="https://github.com/user-attachments/assets/caf841f5-486d-4780-8155-f268516a1356" />


## UDP Traceroute:
sudo traceroute -U www.google.com
## output
<img width="1063" height="236" alt="image" src="https://github.com/user-attachments/assets/39e9650d-0532-4e1b-a4b0-adf550c306ec" />



## ICMP Traceroute:
sudo traceroute  www.google.com
## output

<img width="1506" height="312" alt="image" src="https://github.com/user-attachments/assets/f7995d88-1644-406f-bcb7-bb4502f7bc45" />





## RESULT:
The information gathering techniques tools/procedure were  identified successfully
