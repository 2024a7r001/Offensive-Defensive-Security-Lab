# EXPERIMENT 7: OSINT RECONNAISSANCE USING GOOGLE DORKING AND SHODAN

## 1. AIM
To perform OSINT reconnaissance using Google search operators and Shodan to gather publicly available information and identify exposed services.

## 2. REQUIREMENTS
1. Computer with internet access.
2. Google Search Engine.
3. Shodan Search Engine.
4. Web browser.

## 3. PROCEDURE

**Step 1: Domain-Based Reconnaissance**

Open Google and search `site:gov.in` to find publicly accessible government websites.

**Output:** Screenshot 1 – Google results 

**Step 2: Search for Exposed Directories**

Search `intitle:"index of"` in Google to identify publicly accessible directory listings.

**Output:** Screenshot 2 – Directory listing results.

**Step 3: Find PDF Documents**

Search `inurl:cybersecurity filetype:pdf` to find cybersecurity-related PDF documents.

**Output:** Screenshot 3 – PDF search results.

**Step 4: Find Login Pages**

Search `inurl:login` in Google to identify login-related web pages.

**Output:** Screenshot 4 – Login-page results.

**Step 5: Examine Google Cache**

Search `cache:google.com` to observe the discontinued Google Cache feature.

**Output:** Screenshot 5 – Google Cache search result.

**Step 6: Search Apache Services**

Open Shodan and search `apache` to examine internet-facing Apache web servers.

**Output:** Screenshot 6 – Shodan Apache results.

**Step 7: Search by Port and Country**

Enter `port:23 country:"IN"` in Shodan to find matching hosts in India using Telnet port 23.

**Output:** Screenshot 7 – Shodan port search results.

**Step 8: Hostname-Based Reconnaissance**

Enter `hostname:gov.in` in Shodan to find hosts matching the government-domain filter.

**Output:** Screenshot 8 – Shodan hostname results.

## 4. RESULT
Successfully performed OSINT reconnaissance using Google Dorking and Shodan to discover publicly available information and examine exposed services.

## 5. CONCLUSION
The experiment helped us learn how Google and Shodan collect public information and identify exposed services.
