# InformationGathering
# Information Gathering Techiques

To perform information gathering techniques
AIM:
To perform information gathering techniques using kali linux

# STEPS:
# Step 1:
Install kali linux either in partition or virtual box or in live mode

# Step 2:
Investigate on the various categories of tools as follows:

# Step 3:
Open terminal/browser and try execute necessary commands/use url to perform information gathering

Pen Test Tools Categories:
Following Categories of pen test tools are identified for information gathering:

Footprinting is a part of the reconnaissance process which is used for gathering possible information about a target computer system or network.

http://www.whois.com/whois website to get detailed information about a domain name information including its owner, its registrar, date of registration, expiry, name server, owner's contact information, etc.

# Tested By: lokesh.m<br>
# Register no.: 212224040173<br>
# OUTPUT:<br>
![Screenshot 2025-03-12 210659](https://github.com/user-attachments/assets/d2ea98af-9552-4187-b526-4fc0802617db)

# Finding IP address:
ping command is available on Windows as well as on Linux OS. Following is the example to find out the IP address of saveetha.ac.in.

ping saveetha.ac.in

# output:<br>
![Screenshot 2025-03-12 210829](https://github.com/user-attachments/assets/acff9a4a-0559-4907-af7f-421a21bb8b81)


# Finding Hosting Company:
get further detail by using ip2location.com website.

# output:<br>
![Screenshot 2025-03-12 210959](https://github.com/user-attachments/assets/52d9dfa7-42a3-482b-ba7f-9727aa41a485)


# History of the website:
# Output:<br>
![Screenshot 2025-03-12 211224](https://github.com/user-attachments/assets/4d9d2267-0eaf-4587-ab59-823eb349d450)


# Webserver Fingerprinting:
Netcat:
nc 172.17.52.118 80

# OUTPUT:<br>
![Screenshot 2025-03-12 211311](https://github.com/user-attachments/assets/423cf7a9-efb9-436e-9903-9183c84d802e)


# nmap:
nmap -p 21 -sV --script=banner ftp.vim.org

# OUTPUT:<br>
![Screenshot 2025-03-12 211406](https://github.com/user-attachments/assets/bbd8a50d-54ec-40b1-b235-acb42508f077)


# Whatweb:
whatweb infosys.com

whatweb zoho.com

whatweb -v -a 3 172.17.52.201

# OUTPUT:<br>
![Screenshot 2025-03-12 211452](https://github.com/user-attachments/assets/a9533dcf-6f64-4988-95a2-8f8b901dcc3e)


# httprint:
httprint -h 172.17.52.201 -s /usr/share/httprint/signatures.txt -P0 |more

# OUTPUT:<br>
![Screenshot 2025-03-12 211540](https://github.com/user-attachments/assets/58a2667c-30ed-4ea0-aace-6f1b10652c05)


Tracing the Location
# TCP Traceroute:
sudo traceroute -T www.saveetha.ac.in

# OUTPUT:<br>
![Screenshot 2025-03-12 211622](https://github.com/user-attachments/assets/97a60031-d152-4012-a3b3-927ffa538c70)


# UDP Traceroute:
sudo traceroute -U www.saveetha.ac.in

# OUTPUT:<br>
![image](https://github.com/user-attachments/assets/00448ac7-b0aa-4dda-807c-f85b708fb8e4)


# ICMP Traceroute:
sudo traceroute  www.saveetha.ac.in

# OUTPUT:<br>
![image](https://github.com/user-attachments/assets/c62f2894-fe72-4414-aab0-66302af2b78d)


# RESULT:
The information gathering techniques tools/procedure were identified successfully
