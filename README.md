# Intro to NAT and PAT Overview Guide

**Description/Overview:** This guide provides a brief overview to the networking solutions *Network Address Translation* (NAT) and *Port Address Translation* (PAT), which map one public IP address to multiple private addresses in increasing security and conserving the pool of available IP addresses.

#### Table of Contents

1. [Network Address Translation (NAT) Explained](#nat)
2. [NAT Benefits](#natbenefits)
3. [Port Address Translation (PAT) Explained](#pat)
4. [PAT Benefits](#patbenefits)
5. [NAT and PAT Comparison Table](#comparison)
6. [Supplemental Resources](#supplemental)

<hr />

## 1. <a name="nat">Network Address Translation (NAT) Explained</a>

(TODO)

<hr />

## 2. <a name="natbenefits">NAT Benefits</a>

(TODO)

<hr />

## 3. <a name="pat">Port Address Translation (PAT) Explained</a>

(TODO)

<hr />

## 4. <a name="patbenefits">PAT Benefits</a>

(TODO)

<hr />

## 5. <a name="comparison">NAT and PAT Comparison Table</a>

| | Static NAT | Dynamic NAT | PAT |
| :---: | :---: | :---: | :---: |
| What It Does | Establishes a persistent one-to-one correspondence between a specified private IP address and a specified public IP address. | Establishes a relationship between a private IP and a public IP by borrowing from a pool of addresses, operating on a first-come/first-serve basis in response to a device within a network connecting to a device external to the network. | Establishes many-to-one relationships between multiple private IP addresses and one public IP address, utilizing various port numbers to mark traffic by type. |
| When to Use It | If users external to a network need to connect to the internal network (common for VPN, e-mail, and web servers). | If there are a lot of devices that need to access the internet but should not be accessible outside of the network (especially if there are more private than public IP addresses, and less public IPs available than there are devices). | Implemented in Small Office Home Office (SOHO) networks that need to keep public IP addresses available, while enabling multiple users to be represented externally by one IP address. |

<hr />

## 6. <a name="supplemental">Supplemental Resources</a>

* *[Configuring Network Address Translation and Static Port Address Translation to Support an Internal Web Server (Official Cisco Documentation)](https://www.cisco.com/c/en/us/support/docs/long-reach-ethernet-lre-digital-subscriber-line-xdsl/asymmetric-digital-subscriber-line-adsl/12905-827spat.html)*
* *[Configuring the NAT Device (Official HPE Aruba Networking Article)](https://arubanetworking.hpe.com/techdocs/ArubaOS/AOS_8x_WebHelp/Content/arubaos-solutions/rap/conf-nat-devi.htm?Highlight=nat)*
* *[Intro to Networking - Network Address Translation (NAT) and the Internet (Official UniFi Article)](https://help.ui.com/hc/en-us/articles/115005779887-Intro-to-Networking-Network-Address-Translation-NAT-and-the-Internet)*
