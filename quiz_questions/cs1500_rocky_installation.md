# cs1500 rocky installation

**1. Which command is used within the Red Hat VM to find its current 'inet' IP address?**

- A) ping google.com
- B) ssh root@192.168.0.219
- C) ifconfig
- D) systemctl enable cockpit.socket

**2. When connecting to the VM from a host machine (Mac/Windows), what is the correct SSH command format shown in the tutorial?**

- A) ssh root@[VM_IP_ADDRESS]
- B) ssh admin@[VM_IP_ADDRESS]
- C) connect root@[VM_IP_ADDRESS]
- D) ssh root:9090@[VM_IP_ADDRESS]

**3. What is the first step you must take when the 'authenticity of host' warning appears during an SSH connection?**

- A) Restart the VM
- B) Type 'yes' to accept the certificate
- C) Change the root password
- D) Disable the firewall

**4. Which command is used to activate the Red Hat web console immediately and enable it on boot?**

- A) systemctl set-default multi-user.target
- B) systemctl enable --now cockpit.socket
- C) ifconfig cockpit.socket
- D) ssh root@localhost:9090

**5. What is the default port used to access the Red Hat Web Console?**

- A) 22
- B) 80
- C) 443
- D) 9090

**6. According to the tutorial, what happens to the VM's IP address over time?**

- A) It remains static permanently
- B) It will change over time
- C) It is assigned by the Web Console
- D) It is always 127.0.0.1

**7. Which command is used to set the VM to boot into a non-graphical, multi-user environment?**

- A) systemctl enable --now cockpit.socket
- B) ping google.com
- C) systemctl set-default multi-user.target
- D) ssh root@192.168.0.219

**8. If your VM's IP address is 192.168.0.219, what would be the correct URL to access the Web Console in a browser?**

- A) http://192.168.0.219:22
- B) https://192.168.0.219:9090
- C) ssh://192.168.0.219:9090
- D) https://localhost:80

**9. When accessing the Web Console via a browser, what should you click if you see a 'Your connection is not private' warning?**

- A) Back to safety
- B) Restart your VM
- C) Advanced, then 'Proceed to [IP] (unsafe)'
- D) The 'Help' button

**10. What must you do after running the command 'systemctl set-default multi-user.target' to apply the changes?**

- A) Provide the root password
- B) Restart your VM
- C) Accept the cert
- D) Run ifconfig

