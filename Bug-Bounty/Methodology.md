# Bug Hunter's Methodology

This is a checklist based off Jason Haddix's Bug Hunter Methodology.

## Project Tracking

One of the most important aspects but often overlooked. 

MindMaps - [Xmind](https://github.com/jhaddix/tbhm/blob/master/Project%20(OD).xmind)

## Reconnaissance

### Finding Seeds and Roots

Identify in scope domains

Acquisitions

ASN Enumeration

Reverse WHOIS

Ad and Analytics Relationships

Google

Shodan

### Linked Discovery

**Burp Scan**

[Crawl](https://github.com/GreenPoint-InfoSec/Tutorials-for-Hackers/blob/GreenPoint-InfoSec-Draft/Bug-Bounty/Burp.md#linked-and-javascript-discovery)

**Subdomain Scraping**

- Amass
- Subfinder
- Hunter
- Github-Subdomains
- Shosubgo

**Find Active Hosts**

- httprobe

**Burp Site Mapping**

Visit all the active hosts - use openlist

What did Jason do with things that went to errors? Highlight red to ignore? Remove from Burp? Will Burp do that automatically?

### Subdomain Bruteforcing

- Amass
- ShuffleDNS

### Favicon Analysis

- favfreak
- Shodan API

### Port Analysis

- masscan
- dnmasscan

### Screenshot

- EyeWitness
- Aquatone

### Subdomain Takeover

- nuclei
- SubOver

### CVE Scan

- nuclei
- Sn1per
- gofingerprint
- Nikto

### WaybackURLs

- waybackurls
- meg

## Automation

Rewatch the last 10 mins

## Credential Brute Force

For non-web ports try brute forcing

- Brutespray - https://github.com/x90skysn3k/brutespray

## Content Discovery

- ffuf

### Wordlists

Customise for the target. Use what's out there as a start.

Check these common files:

- robots.txt
- .gitignore
- Makefile
- Rakefile
- Fakefile

[Wordlist Repo](https://github.com/GreenPoint-InfoSec/Wordlists)

**Sources**

https://github.com/jhaddix/tbhm

https://github.com/jhaddix/bug-bounty-reference

Recon - https://www.youtube.com/watch?v=uKWu6yhnhbQ

Wordlists - https://www.youtube.com/watch?v=W4_QCSIujQ4

The Web Applications Hackers Handbook
