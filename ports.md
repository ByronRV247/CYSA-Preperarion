1. Web & Encryption
80/TCP – HTTP (unencrypted web traffic)
443/TCP – HTTPS (encrypted web traffic)
8080/TCP – Alternate HTTP (often used for proxies/web apps)

2. Email
25/TCP – SMTP (email sending)
110/TCP – POP3 (email retrieval)
143/TCP – IMAP (email retrieval)
465/TCP – SMTPS (SMTP over SSL)
587/TCP – SMTP with STARTTLS (secure email submission)
993/TCP – IMAPS (IMAP over SSL)
995/TCP – POP3S (POP3 over SSL)

3. File Transfer
20-21/TCP – FTP (file transfer; 20 = data, 21 = control)
22/TCP – SSH/SCP/SFTP (secure file transfer/remote access)
69/UDP – TFTP (trivial FTP, no auth)
445/TCP – SMB (Windows file sharing)
   
5. Database
1433/TCP – MS-SQL (Microsoft SQL Server)
1521/TCP – Oracle DB
3306/TCP – MySQL
5432/TCP – PostgreSQL

5. Remote Access
23/TCP – Telnet (insecure remote login)
3389/TCP – RDP (Remote Desktop Protocol)
5900/TCP – VNC (virtual network computing)

6. Network Management
161/UDP – SNMP (device monitoring)
162/UDP – SNMP traps (alerts)
514/UDP – Syslog (log collection

7. Vulnerable/High-Risk Services
135/TCP – RPC (Windows)
137-139/TCP – NetBIOS (Windows legacy)
389/TCP – LDAP (directory services)
636/TCP – LDAPS (LDAP over SSL)
5985-5986/TCP – WinRM (Windows Remote Management)

8. VoIP & Collaboration
5060/TCP/UDP – SIP (VoIP signaling)
5061/TCP – SIPS (SIP over TLS)
1720/TCP – H.323 (VoIP)

9. Cloud & Containers
2375/TCP – Docker (unencrypted)
2376/TCP – Docker (TLS)
6443/TCP – Kubernetes API

10. Security Tools
514/UDP – Syslog
1812/UDP – RADIUS (authentication)
636/TCP – LDAPS
