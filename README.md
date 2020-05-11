# Cybersecurity-University-Unit-10
Summary: Setup a honeypot and intercept attacks in the wild.

In this assignment, we will set up a basich honeypot and detect/collect information about an attack

Successful configuration/deployment of a honeypot server has 2 key features:

1) An attack surface that is vulnerable or exposed in some way to network-based attacks
2) A network security feature such as an IDS configured to detect and log such attacks
   Illustration of at least one attack against the honeypot that can be detected or logged in a way that captures information    about the attack or the attacker

Which Honeypot(s) did you deploy
Name	Hostname	Honeypot	Attacks
mhn-honeypot-1-dionaea	mhn-honeypot-1	dionaea	1,653
mhn-honeypot-2-dionaea	mhn-honeypot-2	dionaea	4,231
mhn-honeypot-3-dionaea	mhn-honeypot-3	dionaea	2,001

Did you encounter any issues
Had some issues setting up MHN Honeypot VM using GCP (Mac)

A summary of the data collected: number of attacks, number of malware samples, etc.
TOP 5 Attacker IPs:
173.77.241.134 (700)
192.155.98.197 (481)
91.126.146.225 (123)
68.183.16.108 (111)
104.248.29.221 (54)

TOP 5 Attacked Ports:
23 (725)
5060 (488)
8080 (401)
8088 (54)
445 (21)
