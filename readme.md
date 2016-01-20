## Quick_scan_virus.py

> A simple , fast virus scanner by which you could identify if your files are malware and virus.

---

### Usage
		quick_scan_virus.py %file_path%|%directory_path%|all
		quick_scan_virus.py C:\\Windows\\system32\\kernel32.dll
            scan this file
        quick_scan_virus.py C:\\Windows\\system32\\
            scan all files on current directory
        quick_scan_virus.py all
           scan all files in your computer

### Detail

#### First Intention

**A security tool used to quickly dig APT and other virus in your computer .**

#### What this script actully do ? 

Quick_scan_virus.py extract 「**md5 ,sha1 ,sha256** 」values from files and **map each value** with virus hash provided from famous anti-virus lab (like:`Kaspersky` ,`Symantec` ,`FireEyes` .etc ) .

Warning : The demo virus hash file inside this repo was collected from `Loki` [git:https://github.com/Neo23x0/Loki]
