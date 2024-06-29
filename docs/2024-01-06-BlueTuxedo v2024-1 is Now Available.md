---
title: BlueTuxedo v2024.1 is Now Available
creation_date: January 6, 2024
modification_date: January 6, 2024
---


# BlueTuxedo v2024.1 is Now Available

**# New Year, New Release!**
**
**
BlueTuxedo is now at a place where it can start getting "official releases" - whatever that means for a tool worked on during spare time with no real commitment! Expect a release more-or-less monthly unless life happens.

In this release, we added more information about what BlueTuxedo actually IS to the README, added a couple checks, and improved DHCP server identification. Also, BlueTuxedo is now available in the Powershell Gallery for ease of installation!

**## Improvements:**
* New Data Collected:
	* DnsUpdateProxy group membership
	* Name Protection on DHCP servers
* New Checks:
	* Do ADI DNS zones enforce secure updates?
	* Is the DnsUpdateProxy group membership >0?
* Published to PSGallery: _https://www.powershellgallery.com/packages/BlueTuxedo/2024.1_

**## 
**
**## Known Issues:**
* Certain multi-domain forest configurations result in inability to enumerate ADI Zones.

**## Contributors to this release:**
**_@TrimarcJake_** (code)**_@JimSycurity_** (research and testing)
