

1. **How do you perform a basic scan to identify open ports on a target host `example.com`?**
   - **Answer:** `nmap example.com`

2. **What command would you use to perform a detailed scan on a target IP `192.168.1.1` to determine the operating system?**
   - **Answer:** `nmap -O 192.168.1.1`

3. **How can you scan a range of IP addresses from `192.168.1.1` to `192.168.1.10`?**
   - **Answer:** `nmap 192.168.1.1-10`

4. **What command can you use to perform a scan that detects both open ports and service versions on a target `example.com`?**
   - **Answer:** `nmap -sV example.com`

5. **How do you perform a scan to check for active hosts in a subnet `192.168.1.0/24`?**
   - **Answer:** `nmap -sn 192.168.1.0/24`

6. **What command would you use to perform a scan and show the network services running on open ports of a target `192.168.1.1`?**
   - **Answer:** `nmap -sT 192.168.1.1`

7. **How can you perform a quick scan to identify which hosts are up in the `192.168.1.0/24` network?**
   - **Answer:** `nmap -sn 192.168.1.0/24`

8. **What command is used to perform a stealth SYN scan on a target host `example.com`?**
   - **Answer:** `nmap -sS example.com`

9. **How do you run an `nmap` scan with a custom port range, for example, ports 80 to 100 on `192.168.1.1`?**
   - **Answer:** `nmap -p 80-100 192.168.1.1`

10. **What command can you use to perform a script scan using `nmap` on a target host `example.com`?**
    - **Answer:** `nmap -sC example.com`

11. **How do you perform an `nmap` scan to discover all hosts on a specific network segment without scanning ports?**
    - **Answer:** `nmap -sn 192.168.1.0/24`

12. **What command can you use to perform a scan and include service version detection and operating system fingerprinting on `192.168.1.1`?**
    - **Answer:** `nmap -sV -O 192.168.1.1`

13. **How can you run an `nmap` scan to find out if a specific port, such as port 22, is open on a target host `example.com`?**
    - **Answer:** `nmap -p 22 example.com`

14. **What command would you use to perform an `nmap` scan and output the results in XML format?**
    - **Answer:** `nmap -oX output.xml example.com`

15. **How do you execute an `nmap` scan that will show you the hostnames associated with the IP addresses in the target range?**
    - **Answer:** `nmap -sL 192.168.1.0/24`

16. **What command is used to perform a TCP connect scan on a target `192.168.1.1`?**
    - **Answer:** `nmap -sT 192.168.1.1`

17. **How can you perform a scan that includes `nmap`'s aggressive scan option, which combines multiple scan types and script scanning?**
    - **Answer:** `nmap -A example.com`

18. **What command would you use to scan for open ports on a specific range of IP addresses and also include a timing template to speed up the scan?**
    - **Answer:** `nmap -p 1-65535 -T4 192.168.1.0/24`

19. **How do you run an `nmap` scan with a specific timing template to reduce the likelihood of being detected by intrusion detection systems?**
    - **Answer:** `nmap -T0 example.com` (where `-T0` is the slowest timing template for stealth, but `-T3` or `-T4` are more commonly used for balance between speed and stealth)

20. **What command can you use to run a `nmap` scan with a custom script specified by the user to check for vulnerabilities on `example.com`?**
    - **Answer:** `nmap --script <script-name> example.com`