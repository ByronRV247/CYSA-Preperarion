jump host or bastion hosts 
is a secure intermediaary betweeen internet and data center servers (behind firewall) 
It is specifically designed to control and monitor SSH access to internal systems, reducing direct exposure to the internet.

CASB (Cloud Access Security Broker) 
Key CASB Use Cases:
Detect abnormal login locations to SaaS apps.
Monitor unauthorized data sharing (e.g., confidential files on Dropbox).
Enforce compliance policies (e.g., blocking unapproved cloud services).

Function-as-a-Service(FAAS)
serverless use encode easily 

Key Zero-Trust Trust Factors:
Identity (user/device).
Context (time, location, device posture).
Least Privilege (access limited to what’s needed).
Continuous Verification (not just one-time auth).

Hypervisor Breach = Total Failure: If the VMware ESXi host (hypervisor) is compromised, the attacker gains control over all virtual machines (VMs) and their segmented networks.
Bypasses segmentation entirely (VMs, VLANs, and firewalls become irrelevant).
Allows lateral movement across VMs, data theft, or ransomware deployment.

Real-World Example:
ESXiArgs ransomware attacks (2023) encrypted VMware hosts, disrupting all VMs.
