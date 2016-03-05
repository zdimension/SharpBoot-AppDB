## Please use this template (copy-paste and replace ALL and ONLY the values in UPPERCASE, and of course remove the help texts):
```
- **Name:** NAME
- **Category:** CATEGORY (see the end of this file for existing categories)
- **Regex:** REGEX A regex for detecting files of this software, e.g. ^kali-linux-([0-9.]+)-([0-9a-z]+).iso$
- **Decription:** DESCRIPTION (256 CHARS MAXIMUM)
- **Versions:**
    - **NAME of the version (e.g. Kali Linux 2.0 x86)**
        - **Checksum:** CHECKSUM Checksum of the file (either md5, sha1, sha256 or sha384. If not md5, put sha1: or sha256: or sha384: in front of the checksum)
        - **Download:** DOWNLOAD LINK (a *direct* download link (not some redirecting page), preferrably from the official website)
        - **Regex:** REGEX Regex or filename for detecting that particular version, e.g. ubuntu-15.10(.*)-i386.iso (it can be only a filename, but if it's a regex, put a / in front of it.)
    - **NAME of the version**
        - **Checksum:** CHECKSUM
        - **Download:** DOWNLOAD LINK
        - **Regex:** REGEX
    - REPEAT FOR EVERY VERSION!
(x86 and x64 count as two different versions, so if version 2.0 of the software is available in x86 and x64, create entry 'Software 2.0 x86' and 'Software 2.0 x64')
```


## Categories (please put the name **AND** the ID):

ID | Name
---- | ----
0 | Backup
1 | BIOS
2 | CPU
3 | Linux
4 | Partition
5 | Password
6 | RAM
7 | Recovery
8 | Testing
9 | Utility
10 | Antivirus
11 | Windows
If you want to add a category, just put the name in the template and I will maybe add it. If I don't, I wll replace it by an existing one.


## Example Template:
- **Name:** Ubuntu
- **Category:** 3 Linux
- **Regex:** ^ubuntu(.*).iso$
- **Decription:** Ubuntu is a fast, free and incredibly easy to use Linux distribution.
- **Versions:**
    - **Ubuntu 12.04.5 LTS x86**
        - **Checksum:** 09eb43dcfce2b7246bdd6e8108e755df
        - **Download:** http://releases.ubuntu.com/12.04.5/ubuntu-12.04.5-desktop-i386.iso
        - **Regex:** /ubuntu-12.04(.\*)-i386.iso
    - **Ubuntu Server 15.10 x86**
        - **Checksum:** 0d9ee8b0b0205a8487d6ed8785ee63a8
        - **Download:** http://releases.ubuntu.com/15.10/ubuntu-15.10-server-i386.iso
        - **Regex:** ubuntu-15.10-server-i386.iso
