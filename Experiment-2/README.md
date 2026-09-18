# COM 512 Experiment 2: Simulated Ethical Hacking with Metasploit

## Aim

To perform a safe and controlled exploitation of an intentionally vulnerable virtual machine using the **Metasploit Framework** and understand the basic ethical hacking process.

## Requirements

* Kali Linux
* Metasploitable 2 / intentionally vulnerable VM
* VirtualBox or VMware
* Metasploit Framework
* Isolated Host-Only virtual network

## Procedure

### Step 1: Configure the Lab Network

Kali Linux and the vulnerable target VM were started and configured on the same **Host-Only/isolated network**. The target VM was kept isolated from the public Internet.

**Step 1 Screenshot**

![Metasploit Screenshot](images/metasploit%201.jpeg)

### Step 2: Find the Target IP

The IP address of the target VM was identified using the appropriate network command.

**Target IP:** `________________________`

**Step 2 Screenshot**

![Metasploit Screenshot](images/metasploit%202.jpeg)

### Step 3: Check Connectivity

Connectivity between Kali Linux and the target VM was verified using a ping command.

**Connectivity:** `Successful / Unsuccessful`

**Step 3 Screenshot**

### Step 4: Perform Reconnaissance

Open ports and services running on the target VM were identified. Relevant service and version information was recorded.

| Port | Service | Version/Information |
| ---- | ------- | ------------------- |
|      |         |                     |
|      |         |                     |
|      |         |                     |

**Step 4 Screenshot**

### Step 5: Start Metasploit

The Metasploit Framework was started from the Kali Linux terminal. The Metasploit console was allowed to load successfully.

**Step 5 Screenshot**

### Step 6: Search for a Vulnerability

The reconnaissance results were used to identify a potentially vulnerable service. The Metasploit module database was searched for an exploit applicable to the intentionally vulnerable laboratory VM.

**Step 6 Screenshot**

### Step 7: Select and Configure the Exploit

The required exploit module was selected and its available options were reviewed. The target address, service/port and required payload were configured. All settings were verified before execution.

**Step 7 Screenshot**

### Step 8: Run the Exploit

The selected exploit was executed against the **isolated laboratory target**. The Metasploit console output was observed to determine whether a session was successfully established.

**Step 8 Screenshot**

### Step 9: Verify the Result

If a session was established, it was verified to ensure that it belonged to the intended target VM. Basic system information was collected for documentation. No files were deleted and no destructive changes were made.

**Step 9 Screenshot**

### Step 10: Close the Session

The established session was exited after verification. Metasploit was stopped and the virtual machines were shut down after completion of the experiment.

**Step 10 Screenshot**

## Observation Table

| Parameter          | Observation      |
| ------------------ | ---------------- |
| Attacker           | Kali Linux       |
| Target             | Metasploitable 2 |
| Target IP          | __________       |
| Vulnerable Service | __________       |
| Vulnerability      | __________       |
| Metasploit Module  | __________       |
| Payload            | __________       |
| Session Obtained   | Yes / No         |

## Result

The intentionally vulnerable laboratory VM was tested using the Metasploit Framework in an isolated environment. The experiment demonstrated the basic process of **reconnaissance, vulnerability identification, exploit selection, configuration, controlled exploitation, session verification, and reporting**.

