# Cybersecurity Lab Environment Setup

Building an isolated virtual lab for ethical hacking practice (Networkwalks, Batch B084, Week 1 Project)

## Project Overview
[2-3 sentences in your own words: what the lab is for and why a private network matters.]

## Tools Used
- VirtualBox [your version]
- Kali Linux 2026.2
- NATNetwork (10.0.0.0/24)

## Setup Steps

### 1. NATNetwork
[What you created and the settings you used.]

![NAT Network](01-nat-network.png)

### 2. Kali VM network adapter
[Attached to NAT Network, name NatNetwork, Promiscuous Mode Allow All.]

![Kali adapter](02-kali-adapter.png)

### 3. Static IP and internet access
[How you set 10.0.0.2/24 and the gateway, then tested.]

![IP and ping](03-ip-and-ping.png)

### 4. Clipboard and drag-and-drop
![Clipboard settings](04-clipboard-dragdrop.png)

### 5. Shared folder
![Shared folder](05-shared-folder.png)

### 6. Snapshot
![Snapshot](06-snapshot.png)

## Troubleshooting
**Problem:** The OK button was greyed out in the Kali network settings, with "Invalid settings detected".
**Cause:** No NAT network existed yet, so the Name field said "Not selected".
**Solution:** I created the NatNetwork under File → Tools → Network first, then selected it in the adapter settings.

## Conclusion
[What you built and learned.]

---
*This lab runs on my own computer. All testing is done only in my own virtual environment.*
