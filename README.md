# IT-Support-Lab
I'm a cybersecurity student building hands-on IT support skills. I'll use this repository to document problems I investigate, the steps I take, and what I learn.

## Lab 1: Basic network check

**Goal:** Check my Windows PC's network connection.

**What I did:**
1. Ran `ipconfig`. My Ethernet adapter showed an IPv4 address and a default gateway.
2. Ran `ping 8.8.8.8`. All 4 test messages received a response.
3. Ran `nslookup github.com`. It returned addresses for the website.

**What I learned:** My PC had a connection to my home network, could reach an outside IP address, and could use DNS to look up a website name.
