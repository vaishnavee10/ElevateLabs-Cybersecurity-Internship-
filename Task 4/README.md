# Task 4: Setup and Use a Firewall on Windows

## Objective:
To configure and test basic firewall rules using Windows Defender Firewall.

## Tools Used:
- Windows Firewall (`wf.msc`)
- Command Prompt (Telnet for testing)

## Steps Performed:
1. Opened firewall settings using `wf.msc`.
2. Viewed current inbound rules.
3. Created a new rule to block TCP port 23 (Telnet).
4. Tested with Telnet – connection was blocked.
5. Added a rule to allow TCP port 22 (SSH).
6. Deleted the Telnet block rule to restore original settings.
7. Took screenshots of all steps.

## Summary:
Windows Firewall filters traffic based on rules.  
Port 23 (Telnet) was blocked for security.  
Port 22 (SSH) was allowed for secure access.  
All test changes were removed after use.

## Deliverables:
- Screenshots of:
  - Current firewall settings
  - Block rule (Port 23)
  - Allow rule (Port 22)
