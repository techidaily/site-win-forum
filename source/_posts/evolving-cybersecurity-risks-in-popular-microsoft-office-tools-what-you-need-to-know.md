---
title: Evolving Cybersecurity Risks in Popular Microsoft Office Tools - What You Need to Know
date: 2024-08-28 14:16:40
updated: 2024-08-29 12:41:15
tags:
  - windows
categories:
  - tech
thumbnail: https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/03/office.jpg
---

## Evolving Cybersecurity Risks in Popular Microsoft Office Tools - What You Need to Know

Microsoft has disclosed a zero-day "max severity" vulnerability that impacts several Office and 356 products. Attackers may exploit this vulnerability to steal private data from individuals or organizations. A patch should be available on August 13th.

 The flaw in question, nicknamed "Microsoft Office Spoofing Vulnerability" and tracked as [CVE-2024-38200](https://msrc.microsoft.com/update-guide/vulnerability/CVE-2024-38200), is relatively easy to exploit. An attacker doesn't need to trick their victim into opening a malicious file or running a bad program. They simply need to guide the victim to a website that contains a "specially crafted file," according to Microsoft.

 The following products are impacted by CVE-2024-38200:

* Microsoft Office 2016 (32-bit & 64-bit)
* Microsoft Office 2016 (32-bit & 64-bit)
* Microsoft Office LTSC 2021 (32-bit & 64-bit)
* Microsoft 365 Apps for Enterprise (32-bit & 64-bit)

[MITRE](https://cwe.mitre.org/data/definitions/200.html) says that attackers are highly likely to exploit this vulnerability. For its part, Microsoft marks exploitability as "less likely," meaning that a patch should be available before attackers can figure out how to build the malicious file needed for exploitation. (In any case, individuals or organizations who fail to install the needed security updates will be at risk of attack.)

 Microsoft attributes the discovery of CVE-2024-38200 to PrivSec Consulting's Jim Rush and Synack Red Team's Metin Yunus Kandemir. Evidently, Rush plans to discuss this and other Microsoft Software vulnerabilities at [DEF CON 2024](https://defcon.org/html/defcon-32/dc-32-speakers.html#54496) (which runs from August 8th to the 11th).

 Individuals who utilize an affected version of Microsoft Office should, as always, avoid opening unknown websites (particularly those shared via email). Organizations may take more aggressive steps the mitigate their risk—Microsoft suggests adding sensitive users to the Protected Users Security Group. Blocking TCP 445/SMB outbound in firewall and VPN settings may also reduce potential exposure. Both of these changes can be reversed after installing Microsoft's security patch, which is tentatively planned for August 13th.

 Microsoft is currently working to patch several flaws across the Windows operating system and its first-party apps. One of these flaws, which could let an attacker ["unpatch" a system](https://www.bleepingcomputer.com/news/microsoft/windows-update-downgrade-attack-unpatches-fully-updated-systems/) and take advantage of outdated exploits, is particularly interesting and insidious.

 Source: [Microsoft](https://msrc.microsoft.com/update-guide/vulnerability/CVE-2024-38200) via [BleepingComputer](https://www.bleepingcomputer.com/news/security/microsoft-discloses-office-zero-day-still-working-on-a-patch/)

<ins class="adsbygoogle"
     style="display:block"
     data-ad-format="autorelaxed"
     data-ad-client="ca-pub-7571918770474297"
     data-ad-slot="1223367746"></ins>



<ins class="adsbygoogle"
     style="display:block"
     data-ad-client="ca-pub-7571918770474297"
     data-ad-slot="8358498916"
     data-ad-format="auto"
     data-full-width-responsive="true"></ins>
