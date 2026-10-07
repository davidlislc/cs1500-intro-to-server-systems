# ftp

**1. Which software daemon is used to set up the FTP server in this lesson?**

- A) Apache HTTPD
- B) VSFTPD
- C) Nginx
- D) OpenSSH

**2. Which command is used to install vsftpd and the ftp client on Rocky Linux?**

- A) sudo apt install vsftpd
- B) sudo dnf install vsftpd ftp –y
- C) sudo yum start vsftpd
- D) sudo systemctl install vsftpd

**3. Which port must be allowed through the firewall for FTP traffic?**

- A) 22
- B) 80
- C) 443
- D) 21

**4. What is the full path of the VSFTPD configuration file?**

- A) /etc/ftp/config
- B) /var/log/vsftpd.conf
- C) /etc/vsftpd/vsftpd.conf
- D) /usr/bin/vsftpd.conf

**5. In vsftpd.conf, which setting disables unauthenticated (anonymous) access?**

- A) anonymous_enable NO
- B) local_enable YES
- C) write_enable YES
- D) chroot_local_user YES

**6. What does the 'chroot_local_user=YES' directive accomplish?**

- A) It allows users to browse the entire root filesystem.
- B) It restricts users to their own home directories.
- C) It enables SSL/TLS encryption.
- D) It disables the firewall.

**7. Which command is used to allow FTP access to home directories via SELinux?**

- A) sudo systemctl restart vsftpd
- B) sudo firewall-cmd --reload
- C) sudo setsebool -P ftpd_full_access on
- D) sudo dnf install vsftpd

**8. Where are the VSFTPD logs located by default?**

- A) /etc/vsftpd/vsftpd.conf
- B) /var/log/vsftpd.log
- C) /home/user/logs
- D) /root/vsftpd.log

**9. What is the correct way to enable and start the VSFTPD service simultaneously?**

- A) sudo systemctl enable --now vsftpd
- B) sudo dnf start vsftpd
- C) sudo firewall-cmd --permanent
- D) sudo vsftpd --run

