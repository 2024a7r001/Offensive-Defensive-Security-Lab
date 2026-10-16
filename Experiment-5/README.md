# Sniffing and Session Hijacking

## COM 512 – Offensive and Defensive Security Lab

## 1. Aim
To capture and analyze network traffic using Wireshark and understand ARP spoofing and session hijacking, their impact, and prevention techniques.

## 2. Tools Required
- **Wireshark:** For capturing and analyzing network packets.
- **Computer:** For performing the practical.
- **Test Network:** An authorized lab network or isolated virtual environment.

## 3. Procedure

### Step 1: Open Wireshark
Open Wireshark and select the network interface used for the lab.

**Screenshot 1:** Wireshark main window showing available network interfaces.


### Step 2: Start Packet Capture
Start capturing network traffic on the selected interface and generate some normal network activity.

**Screenshot 2:** Wireshark capturing network packets.


### Step 3: Analyze Network Packets
Observe captured packets and identify protocols such as ARP, TCP, and HTTP, where present. Use Wireshark display filters to find specific packets.

**Screenshot 3:** Captured packets with protocol information.


### Step 4: Study ARP Traffic
Apply the `arp` display filter to observe ARP requests and replies. Study how IP addresses are associated with MAC addresses.

**Screenshot 4:** ARP packets displayed in Wireshark.


### Step 5: Understand ARP Spoofing
In an authorized lab environment, study how forged ARP messages can associate a device's IP address with an incorrect MAC address and potentially redirect network traffic.

**Screenshot 5:** Evidence of ARP traffic or the controlled lab demonstration.



### Step 6: Understand Session Hijacking
Study how an attacker may misuse a stolen or exposed session token to impersonate a user. Use a test application and test accounts in the authorized lab to understand the impact.

**Screenshot 6:** Relevant packet analysis or the controlled session-security demonstration.



### Step 7: Analyze and Apply Prevention Methods
Review the captured traffic and identify security measures, including HTTPS/TLS, secure session cookies, session expiration, network monitoring, and ARP spoofing protection.

**Screenshot 7:** Wireshark analysis showing the relevant packets or security observations.



## 4. Result
Successfully studied network packet capture and analysis using Wireshark. Understood the concepts of ARP spoofing and session hijacking, their potential impact, and methods to reduce these risks.

## 5. Conclusion
This experiment helped us understand how network traffic can be monitored and how weaknesses in network communication and session management can be exploited. We learned the importance of encryption, secure session handling, and network monitoring in improving cybersecurity.

## 6. Security Note
All testing and demonstrations should be performed only on systems and networks for which permission has been granted. No real user credentials or session tokens should be collected or misused.

## 7. Screenshots Folder Structure
