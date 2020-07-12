---
template: post
title: DNS records
slug: dns
draft: false
date: 2020-02-26T06:57:04.409Z
description: supported record types
category: web
tags:
  - www dns
---


* **A**: Address record, which is used to map host names to their IPv4 address.
* **AAAA**: IPv6 Address record, which is used to map host names to their IPv6 address.
* **ALIAS**: A pseudo-record that works like a CNAME but can be safely used at the Zone Apex because it always resolves to A (or AAAA) record(s).
* **CAA**: Certificate Authority (CA) Authorization, which is used to specify which CAs are allowed to create certificates for a domain.
* **CNAME**: Canonical name record, which is used to specify alias names.
* **MX**: Mail exchange record, which is used in routing requests to mail servers.
* **NS**: Name server record, which delegates a DNS zone to an authoritative server.
* **SPF**: Sender Policy Framework record, a deprecated record type formerly used in e-mail validation systems (use a TXT record instead).
* **SRV**: Service locator record, which is used by some voice over IP, instant messaging protocols, and other applications.
* **TXT**: Text record, which can contain arbitrary text and can also be used to define machine-readable data, such as security or abuse prevention information.
