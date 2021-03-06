# Security Policy

### OS Supported Versions

OS Versions that are supported.

CentOS, Debian, Ubuntu, Arch, Fedora, RedHat, Raspbian

### Version Breakdown

| OS              | Supported          | i386               | amd64              | armhf              | arm64              |
| --------------  | ------------------ | ------------------ | ------------------ | ------------------ | ------------------ |
| Amazon Linux    |:x:                 |:x:                 |:x:                 |:x:                 |:x:                 |
| Ubuntu 16.04    |:white_check_mark:  |:white_check_mark:  |:white_check_mark:  |:white_check_mark:  |:white_check_mark:  |
| Ubuntu 18.04    |:white_check_mark:  |:white_check_mark:  |:white_check_mark:  |:white_check_mark:  |:white_check_mark:  |
| Ubuntu 19.04    |:white_check_mark:  |:white_check_mark:  |:white_check_mark:  |:white_check_mark:  |:white_check_mark:  |
| Ubuntu 20.04    |:white_check_mark:  |:white_check_mark:  |:white_check_mark:  |:white_check_mark:  |:white_check_mark:  |
| Raspbian        |:white_check_mark:  |:white_check_mark:  |:white_check_mark:  |:white_check_mark:  |:white_check_mark:  |
| Debian 6.x      |:x:                 |:x:                 |:x:                 |:x:                 |:x:                 |
| Debian 7.x      |:x:                 |:x:                 |:x:                 |:x:                 |:x:                 |
| Debian 8.x      |:white_check_mark:  |:white_check_mark:  |:white_check_mark:  |:white_check_mark:  |:white_check_mark:  |
| Debian 9.x      |:white_check_mark:  |:white_check_mark:  |:white_check_mark:  |:white_check_mark:  |:white_check_mark:  |
| Debian 10.x     |:white_check_mark:  |:white_check_mark:  |:white_check_mark:  |:white_check_mark:  |:white_check_mark:  |
| CentOS 6.x      |:x:                 |:x:                 |:x:                 |:x:                 |:x:                 |
| CentOS 7.x      |:white_check_mark:  |:white_check_mark:  |:white_check_mark:  |:white_check_mark:  |:white_check_mark:  |
| CentOS 8.x      |:white_check_mark:  |:white_check_mark:  |:white_check_mark:  |:white_check_mark:  |:white_check_mark:  |
| CentOS 9.x      |:white_check_mark:  |:white_check_mark:  |:white_check_mark:  |:white_check_mark:  |:white_check_mark:  |
| Fedora          |:white_check_mark:  |:white_check_mark:  |:white_check_mark:  |:white_check_mark:  |:white_check_mark:  |
| RedHat 6.x      |:x:                 |:x:                 |:x:                 |:x:                 |:x:                 |
| RedHat 7.x      |:white_check_mark:  |:white_check_mark:  |:white_check_mark:  |:white_check_mark:  |:white_check_mark:  |
| Arch            |:white_check_mark:  |:white_check_mark:  |:white_check_mark:  |:white_check_mark:  |:white_check_mark:  |
| LXC             |:x:                 |:x:                 |:x:                 |:x:                 |:x:                 |
| OpenVZ          |:x:                 |:x:                 |:x:                 |:x:                 |:x:                 |

### WireGuard Versions

| OS                    | Supported          |
| --------------------  | ------------------ |
| WireGuard Latest Only | :white_check_mark: |


### Reporting a Vulnerability

The critical nature of [Responsible Disclosure](https://en.wikipedia.org/wiki/Responsible_disclosure) when it comes to private communications in the public network space can not be underestimated.  Some peoples lives depend on their communications being kept private.  On a grander scale than the individual level, entire countries can depend on the security and integrity of people who maintain projects like these.  Please be swift in reporting and disclosing vulnerabilities.

We will try to aim for a 90 day turnaround on responsibly disclosed vulnerabilities.
If we have not updated the repository in 90 days from the report it is important to report the vulnerability on the GitHub Issues so that others know that they can no longer trust this repository to effectively protect their security.

We aim for the highest possible level of security without sacrificing on the works by default logic of how software releases should be shipped.  We assume that if the security could be broken between now and the time you've passed away that it's not sufficient for our designs.
