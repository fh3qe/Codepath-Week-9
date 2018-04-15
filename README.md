# Project 9 - Honeypot

Time spent: **4** hours spent in total

> Objective: Set up honeypots using Google Cloud and detect/collect data about an attack.

## Honeypots Deployed
1. Dionaea
2. Snort
3. Glastopf
4. Wordpot

## Issues Encountered
- Not all of the sensors used had logged attacks. The vast majority of attacks detected were from Dionaea and Snort, but Glatopf and Wordpot didn't register any (at time of writing this README)

## Summary of Data Collected
1. Number of attacks: 281
2. Attack Breakdown:
	- pcap: 186
	- SipSession: 31
	- TCP: 25
	- SipCall: 20
	- smbd: 5
	- UDP: 5
	- MSSQLD: 4
3. Top Ports Attacked (# attacks):
	- 5060 (50+)
	- 3389 (30+)
	- 23   (16)
	- 1433 (9)
	- 8080 (5)
4. Top 5 Attacker IPs (# attacks):
	- 46.166.139.181 (50)
	- 191.101.167.37 (34)
	- 182.16.7.58    (31)
	- 58.181.6.81    (9)
	- 77.72.85.25    (8)

## Unresolved Questions
It would've been interesting to see what the long-term distribution of attacker origins would be like. Unsurprisingly, I received a multitude amount of foreign countries but it would be interesting to see where the vast majority of the traffic would be from. Also I didn't get all the honeypots up so it would've been nice to see what it would've been like with all of them up and intercepting attacks.