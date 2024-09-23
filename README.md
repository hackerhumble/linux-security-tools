# linux-security-tools

Linux Exploit Suggester: https://github.com/The-Z-Labs/linux-exploit-suggester/tree/master

# Linux Privilege Escalation Tool

https://github.com/peass-ng/PEASS-ng
<br>
Liniux: https://github.com/peass-ng/PEASS-ng/tree/master/linPEAS

**LinEnum**: https://github.com/rebootuser/LinEnum


**Linux Priv Checker:** https://github.com/sleventyeleven/linuxprivchecker


**Kernel Exploits:** https://github.com/lucyoa/kernel-exploits  --> Not maintained

# Privilege Escalation Resources:

Basic Linux Privilege Escalation - https://blog.g0tmi1k.com/2011/08/basic-linux-privilege-escalation/

Linux Privilege Escalation - https://github.com/swisskyrepo/PayloadsAllTheThings/blob/master/Methodology%20and%20Resources/Linux%20-%20Privilege%20Escalation.md

Checklist - Linux Privilege Escalation - https://book.hacktricks.xyz/linux-unix/linux-privilege-escalation-checklist

Sushant 747's Guide (Country dependant - may need VPN) - https://sushant747.gitbooks.io/total-oscp-guide/content/privilege_escalation_-_linux.html

TCM Resources: https://github.com/TCM-Course-Resources/Linux-Privilege-Escalation-Resources

# Passwords Enumeration:

**Wordlist:** rockyou.txt

**Tools**: Hashcat, john the ripper

# SUID  / SUDO:
# FInd from which path dynamic libraries ar loaded:

`objdump -x <path_to_executable>` : The variable RPATH indicates the search path from where the dynamic libraries are referenced/searched.

* Send custom PATHs when invoking SUDO. This will not work in `env_reset` is done in the sudoers config.
`sudo PATH=$PATH command`
`sudo -E command` -> This passes the current environment to the sudo as well.


