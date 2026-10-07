# cs1500 Crontab

**1. What does the term 'crontab' stand for?**

- A) Cron background
- B) Cron table
- C) Cron tabulation
- D) Cron terminal

**2. How often does the cron daemon wake up to check for scheduled jobs?**

- A) Every second
- B) Every minute
- C) Every hour
- D) Every time the system reboots

**3. Which command is used to install the 'cronie' package on a Yum-based system?**

- A) sudo yum get cronie
- B) sudo yum install -y cronie
- C) sudo apt install cronie
- D) yum start cronie

**4. Where are individual user cron files stored in the system?**

- A)  /etc/cron.d
- B) /var/spool/cron
- C) /usr/bin/cron
- D) /etc/crontab

**5. Which directory is typically used by software packages to install crontab entries?**

- A) /etc/cron.d
- B) /var/spool/cron
- C) /home/user/cron
- D) /etc/crontab

**6. Which crontab command option is used to display the current user's jobs?**

- A) crontab -e
- B) crontab -r
- C) crontab -l
- D) crontab -v

**7. What does the 'crontab -r' command do?**

- A) Runs the crontab immediately
- B) Reloads the configuration files
- C) Removes the current crontab
- D) Restart the cron service

**8. In crontab syntax, what does the first asterisk (*) represent?**

- A) Hour
- B) Day of month
- C) Minute
- D) Month

**9. What values are used to represent Sunday in the 'day of week' field?**

- A) 0 only
- B) 7 only
- C) 1 and 7
- D) 0 and 7

**10. What is the correct syntax to run a script every night at 2:00 AM?**

- A) * 2 * * *
- B) 0 2 * * *
- C) 2 0 * * *
- D) 0 0 2 * *

**11. Which syntax represents running a job every 15 minutes?**

- A) 15 * * * *
- B) */15 * * * *
- C) 0,15,30,45 * * * *
- D) Both B and C

**12. What command is used to check the current status of the crond service?**

- A) sudo systemctl status crond
- B) ps -ef | grep cron
- C) crontab -s
- D) Both A and B

**13. Which environment variable can be set to specify the editor used by 'crontab -e'?**

- A) SET_EDITOR
- B) EDITOR
- C) CRON_EDIT
- D) VISUAL_ED

**14. According to the slides, which OS recently stopped installing crontab by default?**

- A) Ubuntu
- B) Rocky Linux
- C) Debian
- D) CentOS

**15. What is the range for the 'Month of year' field in crontab?**

- A) 0-11
- B) 1-12
- C) 0-12
- D) 1-31

**16. Which file is generally changed by hand by system administrators for system-wide tasks?**

- A) /etc/crontab
- B) /var/spool/cron/root
- C) /etc/cron.d/admin
- D) /usr/bin/crontab

**17. What is the purpose of the 'crontab -e' command?**

- A) Execute the cron job now
- B) Exit the cron daemon
- C) Edit the current crontab
- D) Erase all cron settings

**18. In Method #2 for editing crontabs, what does 'crontab mycrontab' do?**

- A) Deletes the file 'mycrontab'
- B) Loads the contents of 'mycrontab' into the cron system
- C) Lists the contents of the file
- D) Compares the file with the current crontab

**19. Which special string can be used to run a job every time the system reboots?**

- A) @daily
- B) @restart
- C) @reboot
- D) @startup

**20. What is the crontab syntax for running a job at 2 AM on the 15th of every month?**

- A) 0 2 * 15 *
- B) 15 2 * * *
- C) 0 2 15 * *
- D) */15 2 * * *

