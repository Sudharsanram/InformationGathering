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

### Pen Test Tools Categories:

Following Categories of pen test tools are identified for information gathering: Footprinting is a part of the reconnaissance process which is used for gathering possible information about a target computer system or network. http://www.whois.com/whois website to get detailed information about a domain name information including its owner, its registrar, date of registration, expiry, name server, owner's contact information, etc.

## OUTPUT:
![267842400-6a9f4cae-171f-4a15-9f16-2183db885f28](https://github.com/Sudharsanram/InformationGathering/assets/119393980/37f800a1-0dc0-422b-83d3-cbf60f800a30)

### Finding IP address:

ping command is available on Windows as well as on Linux OS. Following is the example to find out the IP address of saveetha.ac.in.
```
ping saveetha.ac.in
```
## OUTPUT:

![267842514-daaa3ee1-e043-4971-a854-af26c61b5f83](https://github.com/Sudharsanram/InformationGathering/assets/119393980/2ef41075-d6a5-4a87-a648-73d2022829fc)

### Finding Hosting Company

get further detail by using ip2location.com website.

## OUTPUT:
![267842596-b0914500-f468-4a40-835a-7bd1417352b0](https://github.com/Sudharsanram/InformationGathering/assets/119393980/f70342d0-90cf-42e9-9858-0373d5f45550)

#### History of the website:

### Output:
https://web.archive.org/

![267842712-60b168b7-3495-40a5-bdfe-d2d6472fbdd5](https://github.com/Sudharsanram/InformationGathering/assets/119393980/c36a1031-83e0-4ae1-a016-24e208ab7b61)

```
nc 172.17.52.118 80
```
![267842755-9753fbf4-69e2-47f5-b5e2-7e4cf8c13e67](https://github.com/Sudharsanram/InformationGathering/assets/119393980/b9f66015-fdc3-4cb1-abc2-bdb68b21fa37)

### nmap:
```
nmap -p 21 -sV --script=banner ftp.vim.org
```

## OUTPUT:

![267842839-04cf9242-82ca-4616-8c5e-dd40b65d5d1b](https://github.com/Sudharsanram/InformationGathering/assets/119393980/89a8ef33-9d25-4632-83ab-27cf030b9857)

### Whatweb:
```
whatweb infosys.com
```
```
whatweb zoho.com
```
```
whatweb -v -a 3 172.17.52.201
```
## OUTPUT:

![267842976-9a657cbd-42b5-43f9-bdc1-238e27e2afc5](https://github.com/Sudharsanram/InformationGathering/assets/119393980/941d89b6-2aa2-4c4c-9f0a-721a2058008d)

### httprint:
```
httprint -h 172.17.52.201 -s /usr/share/httprint/signatures.txt -P0 |more
```

## OUTPUT:
![267843047-55253bc3-6c40-48d5-8a71-b3a47094b564](https://github.com/Sudharsanram/InformationGathering/assets/119393980/f90dc3d5-6873-4079-b707-782f58211bd5)

### Tracing the Location
### TCP Traceroute:
```
sudo traceroute -T www.saveetha.ac.in
```

## OUTPUT:
![267843097-6eb0602e-82a2-47e7-b179-a6e21c3f2fe5](https://github.com/Sudharsanram/InformationGathering/assets/119393980/1045dd18-7e9f-4d73-9520-56f98052fc74)

### UDP Traceroute:
```
sudo traceroute -U www.saveetha.ac.in
```
## OUTPUT:
![267843184-e74c96f6-45fc-4b9a-b2a1-6954751f9bbe](https://github.com/Sudharsanram/InformationGathering/assets/119393980/1eeb46d6-877f-4a28-840a-eeb67630a59b)

### ICMP Traceroute:
```
sudo traceroute  www.saveetha.ac.in
```
## OUTPUT:
![267843240-9a03b174-8b34-464d-ab54-57a6d7a6e48c](https://github.com/Sudharsanram/InformationGathering/assets/119393980/671af1a8-2b09-45af-be03-58fd7ff66613)

## RESULT:
The information gathering techniques tools/procedure were  identified successfully
