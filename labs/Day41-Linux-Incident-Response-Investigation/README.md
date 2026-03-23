# Day 41 - Linux Incident Response

**Focus:** Investigating Linux attack surfaces via the TryHackMe Linux Incident Surface room.

## Key Areas Explored

### Processes & Network Communication
- Analyzed suspicious processes and active network connections using CLI tools: `ps`, `lsof`, `osquery`.  
- Learned to identify unusual behavior and potential indicators of compromise.

### Persistence Investigation
- Examined hidden cronjobs, unauthorized account creation, and suspicious `systemd` services.  
- Practiced techniques attackers use to maintain long-term access on Linux systems.

### Footprints on Disk
- Investigated malicious packages and their installation scripts (`/DEBIAN/postinst`).  
- Reviewed `dpkg.log` to trace package installation history and detect anomalies.

### Linux Log Analysis
- Studied logs: `syslog`, `auth.log`, and `dpkg.log`.  
- Used tools like `grep`, `zgrep`, and `journalctl` to identify suspicious activity, including unauthorized package installations and service behavior.

## Key Takeaways
- Linux incident response relies heavily on CLI skills, log analysis, and understanding system internals.  
- Detecting persistence mechanisms and suspicious processes is critical for effective investigation.  
- Hands-on practice strengthens the ability to respond to real-world Linux security incidents.

