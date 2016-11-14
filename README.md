[![Build Status](https://travis-ci.org/Fernando0069/check_server.svg?branch=master)](https://www.refsolutions.com)
[![Website](https://img.shields.io/website-up-down-green-red/http/shields.io.svg?style=plastic)](https://www.google.es)
[![Pay](https://img.shields.io/badge/%24-free-%23a10000.svg?style=plastic)](https://www.google.es)
[![GitHub license](https://img.shields.io/badge/license-GPL3-brightgreen.svg)](https://www.gnu.org/licenses/gpl-3.0.en.html)

# check_server
> Check Server - Security auditing and hardening tool, for UNIX-based systems.

You can be used to install "check_server" on systems running: `Fedora`, `RHEL`, `CentOS`, `Debian`, `Ubuntu`, `SUSE`, `openSUSE`, `AIX`, `Solaris` and others.

### Main goals:
- Automated security auditing.
- Detect vulnerabilities (comming soon).

### The software aims to also assist with:
- Configuration management.
- Software patch management.
- System hardening.
- Penetration testing.
- Intrusion detection.

### License:
- GPLv3

### Typical users of the software:
- System administrators
- Auditors
- Security officers
- Security professionals

### Git
1. Clone or download the project files (**no compilation nor installation** is required) ;
       - git clone https://github.com/CISOfy/lynis
2. Execute:
       - ./lynis audit system
        
If you want to run the software as `root`, we suggest changing the ownership of the files. Use `chown -R 0:0` to recursively alter the owner and group and set it to user ID `0` (`root`).
