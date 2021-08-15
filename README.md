# Ethical Hacking

## IP Addres

### Types

1. Physical Addressing
    - Mac Address
2. Logical Addressing
    - IPv4 ( It is a 32 bit logical address, 4 Octet )
        ```
                        255 -> Network Id   |   0 -> Host Id
        ```
        - Public ( e.g. WAN )
        ```
        Address Class       Range                                   Default Subnet Mask
        A                   10.0.0.0 to 126.255.255.255              255.0.0.0
        B                   172.16.0.0 to 172.31.255.255            255.255.0.0
        C                   192.168.0.0 to 192.168.255.255            255.255.255.0
        ...
        ```
        - Private ( e.g. LAN )
        ```
        Address Class       Range                                   Default Subnet Mask
        A                   1.0.0.0 to 126.255.255.255              255.0.0.0
        B                   128.0.0.0 to 191.255.255.255            255.255.0.0
        C                   192.0.0.0 to 223.255.255.255            255.255.255.0
        D                   224.0.0.0 to 239.255.255.255            Reserved for Multi-Casting
        E                   240.0.0.0 to 254.255.255.255            Experimental
        ```
        - ( Virtual Private Network )

        `127.0.0.0 to 127.255.255.255 are reserved for loop back testing`
    - IPv6

## Protocols
1. Http
    - Http1.1 ( Http )
    - Http2
    - Http3
    - Https ( Secure )
        - SSL
        - ( Encryption / Decryption )
    - Hsts
2. Ftp
3. Tcp

## Types of Networks
1. PAN ( Personal Area Network )
    - HotSpot
2. LAN ( Local Area Network )
    - Ethernet
3. WAN ( Wide Area Network )
    - Internet
4. MAN

## OSI Layers
1. Application Layer
2. Presentation Layer
3. Session Layer
4. Transport Layer
5. Network Layer
6. Data Links Layers
7. Physical Layer

## Proxy
1. VPN
    - OpenVPN

## Web
1. Surface Web
2. Hidden Web
    - Deep Web
        - Dark Web

## Foot-Printing & Reconisense
1. Active ( Direct Interaction )
2. Passive ( InDirect Interaction )

## Google Dorking
    - filetype:pdf
    - site:gov.in

**Note:** Google Hacking Database ( G.H.D.B ) , help finding google dorks
**Note:** Google Advanced Search , helps search flexibly well
**Note:** Whois Domain Tools Search | website.grader.com | Alexa , helps search Information about Domains etc
**Note:** SubDomain Finders

- searchdns.netcraft.com
- sublist3r
- recon-ng

- mxtoolbox.com reverse lookup
- waybackmachine

## Linux Structure
- Root Users
- Root Home
- Root Directory

## Command Structure
- Command `ls`
- Options `--help` `-alt`
- Arguments `/Desktop`
- Example
    ```
    ls -l /Desktop
    ```

## Linux Basic Commands
1. `apt-get update`
2. `apt-get upgrade` `apt-get full-upgrade`
3. `ls` `ls -a` `ls -l` `ls -al` `ls -r` `ls -t` `ls -rt` `ls --help`
4. `cd` `cd /` `cd ../` `cd -` `pwd`
5. `mkdir` `mkdir -p` `rmdir` `rm -r` `rm -r -i` `rm -rf`
6. `touch` `rm` `rm -rf abc.txt`
7. `history` `history -c`
8. `man ls` `man apt` `man cd`
9. `ifconfig` `ifconfig -a`
10. `ps` `ps -aux` `kill [pid]` `Ctrl+z` `fg [jobId]`
11. `passwd` **#** **$**
12. `sudo` `apt` `apt-get`
13. `openvpn` `route`
14. `ping [url]`
15. `apt update && apt full-upgrade` `wget -q -O -`
16. `Ctrl+c` `clear` `exit`
17. `Tab` `Double Tab`
18. `Shift+pgUp` `Shift+pgDown`
19. `Ctrl+r` 
20. `Ctrl+a` `Ctrl+e` 
21. `Ctrl+k` `Ctrl+y`
22. `cat` `less` `head` `tail`
23. `cp` `cp -i` `cp -r` `mv`
24. `apt` `apt-cache search` `apt-cache show` `apt-get install [-y]` 
25. `apt-get remove` `apt-get purge` `apt autoremove`
26. `dpkg -l` `dpkg -i package.deb` `dpkg -r package.deb`
27. `apt-get + apt => apt`
28. `apt edit-sources` => `nano /etc/apt/sources.list`
29. `tar c` `tar r` `tar t` `tar x` `tar v` `tar f file` `tar xvf archive.tar -C ~/Desktop/`
30. **gzip** **bzip2**
31. `tar zcvf compressed.tar.gz file1 file2` `tar jcvf compressed.tar.bz2 file1 file2`

## Off Topics
- DOD
- TSL/IP
- DNS
- Whois