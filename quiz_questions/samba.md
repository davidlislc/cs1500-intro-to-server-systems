# samba

**1. What is Samba primarily used for?**

- A) Compiling C++ code on Windows
- B) An open-source implementation of the SMB/CIFS protocol for cross-platform sharing
- C) A Linux-only web server for hosting static sites
- D) A database management system for Rocky Linux

**2. Which operating systems can act as clients to a Samba server for file and print services?**

- A) Only Windows
- B) Only macOS
- C) Windows, macOS, and Linux
- D) Only Linux

**3. Which command is used to install Samba and its common tools on Rocky Linux?**

- A) sudo apt install samba
- B) sudo dnf install samba samba-common samba-client –y
- C) sudo yum get samba-all
- D) install-samba --now

**4. In the provided tutorial, what is the specific path created for the shared directory?**

- A) /home/samba/data
- B) /var/samba/share
- C) /srv/samba/shared
- D) /etc/samba/public

**5. Which command is used to set the directory permissions to 775 for the Samba share?**

- A) sudo chmod -R 775 /srv/samba/shared
- B) sudo chown 775 /srv/samba/shared
- C) sudo set-perms 775 /srv/samba/shared
- D) sudo chmod 777 /srv/samba/shared

**6. What does the 'guest ok = yes' parameter in smb.conf signify?**

- A) It allows users to log in without a password
- B) It disables all security for the share
- C) It enables guest access to the share
- D) It allows the 'nobody' user to delete files

**7. Before adding a user to Samba with 'smbpasswd', what must be done first?**

- A) Create a Windows Active Directory account
- B) Add a system user to the Linux OS
- C) Restart the router
- D) Disable the firewall

**8. What command is used to enable a Samba user account?**

- A) sudo smbpasswd -e <username>
- B) sudo smbpasswd -a <username>
- C) sudo smb-enable <username>
- D) sudo systemctl enable smbuser

**9. Which command starts both the smb and nmb services immediately and enables them on boot?**

- A) sudo systemctl start samba
- B) sudo systemctl enable --now smb nmb
- C) sudo service samba restart
- D) sudo start-samba-services

**10. What must be done to the firewall to allow Samba traffic?**

- A) Disable the firewall entirely
- B) Run 'sudo firewall-cmd --permanent --add-service=samba'
- C) Open port 80 and 443
- D) Run 'sudo firewall-cmd --add-port=1234'

**11. How do you access the share from a Windows machine?**

- A) Enter http://<Server-IP> in Chrome
- B) Enter \\<Server-IP>\PublicShare in File Explorer
- C) Use the 'ssh' command in PowerShell
- D) Enter smb://<Server-IP> in Internet Explorer

**12. Which tool is used on Linux to access a Samba share via the command line?**

- A) smbclient
- B) ftp-samba
- C) ssh-share
- D) get-samba

