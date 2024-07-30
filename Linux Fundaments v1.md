
### Basic Problems

1. **How do you list all files, including hidden files, in a directory?**
   - **Answer:** Use the command `ls -a`.

2. **How can you create a directory named "projects" in your home directory?**
   - **Answer:** Use the command `mkdir ~/projects`.

3. **What command would you use to create an empty file named "report.txt"?**
   - **Answer:** Use the command `touch report.txt`.

4. **How do you copy a file named "data.txt" from your home directory to the "/tmp" directory?**
   - **Answer:** Use the command `cp ~/data.txt /tmp/`.

5. **How can you rename a file from "oldname.txt" to "newname.txt"?**
   - **Answer:** Use the command `mv oldname.txt newname.txt`.

6. **What command changes the permissions of "script.sh" to make it executable by the owner and readable by everyone else?**
   - **Answer:** Use the command `chmod 744 script.sh`.

7. **How do you display the contents of a file named "example.txt"?**
   - **Answer:** Use the command `cat example.txt`.

8. **How can you find all occurrences of the word "error" in a file named "logfile.log"?**
   - **Answer:** Use the command `grep 'error' logfile.log`.

9. **Which command can you use to check the current CPU and memory usage on the system?**
   - **Answer:** Use the command `top`.

10. **How do you install the "curl" package using a package manager?**
    - **Answer:** Use the command `sudo apt install curl`.

11. **How do you create a new user named "john"?**
    - **Answer:** Use the command `sudo useradd john`.

12. **How can you schedule a cron job to run a script called "backup.sh" every day at 2 AM?**
    - **Answer:** Use the command `crontab -e` and add `0 2 * * * /path/to/backup.sh`.

13. **Which command can you use to display the IP address of the system's network interfaces?**
    - **Answer:** Use the command `ip addr show`.

14. **How do you check disk usage in a human-readable format?**
    - **Answer:** Use the command `df -h`.

15. **How can you allow SSH connections through the firewall using `ufw`?**
    - **Answer:** Use the command `sudo ufw allow 22`.

16. **How do you delete a file named "unwanted.txt"?**
    - **Answer:** Use the command `rm unwanted.txt`.

17. **How can you view the manual page for a command, like "ls"?**
    - **Answer:** Use the command `man ls`.

18. **What command would you use to find out your current working directory?**
    - **Answer:** Use the command `pwd`.

19. **How do you create a symbolic link named "shortcut" that points to "original_file.txt"?**
    - **Answer:** Use the command `ln -s original_file.txt shortcut`.

20. **How can you display the last 10 lines of a file named "log.txt"?**
    - **Answer:** Use the command `tail log.txt`.

21. **What command would you use to find out the disk usage of a directory named "data"?**
    - **Answer:** Use the command `du -sh data`.

22. **How do you display all running processes on the system?**
    - **Answer:** Use the command `ps aux` or `top`.

23. **How can you change the owner of a file named "file.txt" to user "alice"?**
    - **Answer:** Use the command `sudo chown alice file.txt`.

24. **What command is used to display the first 10 lines of a file named "textfile.txt"?**
    - **Answer:** Use the command `head textfile.txt`.

25. **How do you count the number of lines, words, and characters in a file named "words.txt"?**
    - **Answer:** Use the command `wc words.txt`.

26. **How can you restart a service named "nginx" on the system?**
    - **Answer:** Use the command `sudo systemctl restart nginx`.

27. **What command can you use to check the current date and time?**
    - **Answer:** Use the command `date`.

28. **How do you extract a tarball named "archive.tar.gz" into the current directory?**
    - **Answer:** Use the command `tar -xzf archive.tar.gz`.

29. **How can you find all files larger than 100 MB in the "/var/log" directory?**
    - **Answer:** Use the command `find /var/log -size +100M`.

30. **What command would you use to display the kernel version of your Linux system?**
    - **Answer:** Use the command `uname -r`.