# Intro to NAT and PAT Overview Guide

**TODO:** A brief introductory guide to NAT and PAT as fundamental computer networking concepts.

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
| When to Use It | | | |

<hr />

## 6. <a name="supplemental">Supplemental Resources</a>

* *[Configuring Network Address Translation and Static Port Address Translation to Support an Internal Web Server (Official Cisco Documentation)](https://www.cisco.com/c/en/us/support/docs/long-reach-ethernet-lre-digital-subscriber-line-xdsl/asymmetric-digital-subscriber-line-adsl/12905-827spat.html)*
* *[Configuring the NAT Device (Official HPE Aruba Networking Article)](https://arubanetworking.hpe.com/techdocs/ArubaOS/AOS_8x_WebHelp/Content/arubaos-solutions/rap/conf-nat-devi.htm?Highlight=nat)*
* *[Intro to Networking - Network Address Translation (NAT) and the Internet (Official UniFi Article)](https://help.ui.com/hc/en-us/articles/115005779887-Intro-to-Networking-Network-Address-Translation-NAT-and-the-Internet)*
