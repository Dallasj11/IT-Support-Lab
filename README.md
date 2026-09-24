# IT-Support-Lab
I'm a cybersecurity student building hands-on IT support skills. I'll use this repository to document problems I investigate, the steps I take, and what I learn.

## Lab 1: Basic network check

**Goal:** Check my Windows PC's network connection.

**What I did:**
1. Ran `ipconfig`. My Ethernet adapter showed an IPv4 address and a default gateway.
2. Ran `ping 8.8.8.8`. All 4 test messages received a response.
3. Ran `nslookup github.com`. It returned addresses for the website.

**What I learned:** My PC had a connection to my home network, could reach an outside IP address, and could use DNS to look up a website name.

## Lab 2: Investigating a Bluetooth warning

**Goal:** Practice investigating a Windows system event.

**What I found:** In Event Viewer → Windows Logs → System, I found a warning from `HidBth`, Event ID 2. It said a Bluetooth input device went out of range or became unresponsive.

**My investigation:** I considered the Bluetooth devices I use and checked when the event occurred. My PS5 controller was a possible source.

**Conclusion:** This was likely a temporary controller disconnect. The event did not identify the device, so I could not confirm the cause from the log alone.
