# Local Network Port Scanning — Internship Task 1

I performed a local network scan using Nmap to identify active devices and open ports.  
- IP range scanned: `192.168.51.0/24`
- Active host found: `192.168.51.191`
- Open ports: 135, 139, 445, 1521, 3306, 7070, 8000, 8089  
- Captured network packets using Wireshark during the scan.

# Identified risks:
- SMB ports (139, 445) can expose the system to file-sharing attacks.
- Database ports (1521, 3306) may allow unauthorized access.
- Unknown ports (8089) need investigation.

Files included:
- `scan_results.txt` — Nmap scan output
- `nmap_scan_capture.pcapng` — Wireshark capture
