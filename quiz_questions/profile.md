# profile

**1. Which file defines common tasks and global variables, such as PATH and TERM, for all users on a system?**

- A) ~/.bashrc
- B) /etc/profile
- C) ~/.bash_profile
- D) /bin/bash

**2. When does the bash shell search for and load commands from the .bash_profile file?**

- A) Every time a command is executed
- B) Only when the server restarts
- C) When a user logs in
- D) Every five minutes via a cron job

**3. What is a primary difference between /etc/profile and ~/.bash_profile?**

- A) /etc/profile is for batch mode, while ~/.bash_profile is for interactive mode
- B) /etc/profile applies to all users, while ~/.bash_profile applies only to the current user
- C) ~/.bash_profile is executed before /etc/profile
- D) /etc/profile cannot be edited by the root user

**4. Which command is used to apply changes made to .bash_profile without logging out and back in?**

- A) run .bash_profile
- B) source .bash_profile
- C) execute .bash_profile
- D) update .bash_profile

**5. Why might a user choose to use 'bash -lc' in a cron job or Docker container?**

- A) To make the script run faster
- B) To bypass security permissions
- C) To ensure environment variables from the login shell are loaded
- D) To prevent the script from accessing the internet

**6. Which file is described as the equivalent to .bash_profile but for non-login shells or batch mode?**

- A) .bashrc
- B) /etc/config
- C) .profile_backup
- D) ~/.bash_login

**7. To invoke a shell script named 'for.sh' from any directory without using './', what must be done?**

- A) Move the script to the root directory
- B) Add the script's directory to the PATH variable in .bash_profile
- C) Rename the script to 'for.exe'
- D) Change the file permissions to 777

