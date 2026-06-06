# OPNOTE-200

| Host | IP | Role | Owned | User | Root/Admin |
|------|------|------|------|------|------|

### Credential Reuse Tracker

| Username | Password | Hash | Source | Reused? |
|----------|----------|------|--------|---------|

### Internal Routes

| Pivot Host | Reachable Subnet | Method |
|------------|------------------|---------|

### Important Observations

- Observation 1
- Observation 2

What does this machine actually do?

Web
Database
Development
Backup
Domain Controller
File Server
Unknown
Enumeration Journal
First Impressions

What immediately stands out?

Strange ports?
Weird banners?
Old software?
Credentials exposed?
Internal services?
Open Services
Port	Service	Version	Interesting?
Service Attack Paths
FTP

□ Anonymous login

□ Upload capability

□ Download sensitive files

□ Password reuse opportunities

Notes:

SMB

□ Null sessions

□ Readable shares

□ Writable shares

□ Credentials

□ Scripts

□ Backup archives

□ Password patterns

□ Internal documentation

Notes:

SSH

□ Password authentication

□ Key authentication

□ Reused credentials

□ Private keys discovered

Notes:

Web
Discovery

□ robots.txt

□ backup files

□ hidden directories

□ virtual hosts

□ API endpoints

□ source disclosure

Authentication

□ default credentials

□ password spraying

□ username enumeration

□ registration abuse

□ session weaknesses

Input Testing

□ SQLi

□ Command Injection

□ File Upload

□ SSTI

□ XXE

□ SSRF

□ LFI

□ RFI

Questions

Can this application:

□ Read files?

□ Write files?

□ Execute commands?

□ Reach internal services?

□ Authenticate as another user?

Exploitation Notes
Entry Vector

How did I get in?

Payload Used
Shell Quality

□ Stable

□ Interactive

□ Privileged

□ Unstable

Linux Escalation Investigation
Current Context

User:

Groups:

Hostname:

Kernel:

Credentials

□ Config files

□ Backups

□ SSH keys

□ History files

□ Databases

□ Environment variables

Privilege Opportunities

□ sudo

□ SUID

□ Capabilities

□ Cron

□ Writable scripts

□ Docker

□ LXD

□ NFS

□ Kernel

Questions

Can I become another user?

Can I steal credentials?

Can I hijack execution flow?

Can I modify something trusted?

Windows Escalation Investigation
Current Context

User:

Groups:

Privileges:

Integrity Level:

Credentials

□ SAM

□ LSA Secrets

□ Stored credentials

□ Browser data

□ Configuration files

□ RDP files

Privilege Opportunities

□ SeImpersonatePrivilege

□ Services

□ Scheduled Tasks

□ Registry

□ Startup

□ DLL Hijacking

□ Token Abuse

□ AlwaysInstallElevated

Questions

Can I impersonate?

Can I modify a privileged process?

Can I restart something important?

Can I abuse trust relationships?

Active Directory Battle Map
What Do I Control?

Users:

Groups:

Computers:

Sessions:

What Can Be Abused?

□ Kerberoasting

□ ASREP Roasting

□ ACL Abuse

□ LAPS

□ Delegation

□ Password Reuse

□ Local Admin Reuse

□ GPP

□ RBCD

BloodHound Notes

Interesting Paths:

Potential Escalations:

Dead Ends:

Pivoting Notebook
New Networks Discovered
Network	Through	Notes
Internal Targets
Host	Why Interesting?
Can I Reach?

□ Database Servers

□ Domain Controllers

□ Backup Servers

□ Jump Hosts

□ Development Systems

Loot Locker
Passwords
Hashes
Keys
Configurations
Internal Documents
Backups
Screenshots
Rabbit Holes
Lead

Why did it look promising?

Investigation
Outcome

Dead End / Useful

Exam Reality Check

Before moving on:

□ Have I tried all credentials?

□ Have I checked every share?

□ Have I looked for password reuse?

□ Have I checked hidden web content?

□ Have I manually enumerated?

□ Am I assuming instead of verifying?

□ Is there another attack path?

Ownership Summary
User Flag

Location:

Method:

Root/Admin Flag

Location:

Method:

Attack Story

Initial Discovery

↓

Enumeration

↓

Vulnerability Identification

↓

Exploitation

↓

Privilege Escalation

↓

Pivoting

↓

Objective Complete
