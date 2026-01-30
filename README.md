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
<img width="1907" height="1050" alt="Screenshot 2026-01-30 085438" src="https://github.com/user-attachments/assets/bd08c4c5-6f5d-4548-a3fb-29e054b0aace" />


## Finding IP address:
ping command is available on Windows as well as on Linux OS. Following is the example to find out the IP address of facebook.com.

## output
<img width="669" height="283" alt="image" src="https://github.com/user-attachments/assets/5d91b27f-7db3-490b-993d-1a572f75001c" />



## Finding Hosting Company
get further detail by using ip2location.com website.
## output
<img width="1907" height="1035" alt="Screenshot 2026-01-30 085615" src="https://github.com/user-attachments/assets/945a0ec4-5376-4e6c-8dd5-6253d2077356" />



## History of the website:
## output
https://web.archive.org/
<img width="1905" height="1052" alt="Screenshot 2026-01-30 085458" src="https://github.com/user-attachments/assets/b8b5e21c-6028-42c4-a628-a38233a4c93b" />


# Webserver Fingerprinting:

## Netcat:
sudo nc example.com 80
GET / HTTP/1.1
Host: example.com

<img width="880" height="576" alt="Screenshot 2026-01-30 091559" src="https://github.com/user-attachments/assets/18cf426d-f827-49d6-9b8b-1342e08ba7a3" />


## nmap:
### output
<img width="886" height="351" alt="image" src="https://github.com/user-attachments/assets/b3d3fb31-93d2-4fde-ba72-dba2ac48afb5" />

## Whatweb
### output

<img width="885" height="179" alt="image" src="https://github.com/user-attachments/assets/dbf794a9-b659-418f-b62b-36b32bd73eaf" />

## httprint
### output

<img width="1107" height="536" alt="image" src="https://github.com/user-attachments/assets/8122f843-6cd1-4a7e-ace4-9f163ae8a4c4" />




# Tracing the Location
TCP Traceroute:
sudo traceroute -T www.figma.com
## output
<img width="878" height="119" alt="image" src="https://github.com/user-attachments/assets/4d858a30-cab4-4889-adb7-62a8056eec40" />


## UDP Traceroute:
sudo traceroute -U www.figma.com
## output

<img width="773" height="497" alt="image" src="https://github.com/user-attachments/assets/929397db-3b50-4f85-88c8-8a834797573d" />


## ICMP Traceroute:
sudo traceroute  www.figma.com
## output
<img width="794" height="380" alt="image" src="https://github.com/user-attachments/assets/6313d45c-1537-4691-8277-969e889431e3" />






## RESULT:
The information gathering techniques tools/procedure were  identified successfully
