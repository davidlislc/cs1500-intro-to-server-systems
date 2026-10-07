# cs1500: users and groups

**1. Which user on a Linux system has a UID of '0' and holds extra privileges?**

- A) The system administrator
- B) The superuser 'root'
- C) The primary group owner
- D) The kernel process

**2. What is the maximum number of groups a single user can belong to in Linux?**

- A) Only one group
- B) Exactly two groups
- C) Several groups
- D) No groups

**3. Which command is used to display information about a specific user, such as their UID and group memberships?**

- A) whoami
- B) userinfo
- C) id username
- D) cat /etc/passwd

**4. In which file is group information stored on a Linux system?**

- A) /etc/passwd
- B) /etc/shadow
- C) /etc/group
- D) /etc/gshadow

**5. What character is used to divide data fields in the /etc/passwd and /etc/group files?**

- A) Comma (,)
- B) Semicolon (;)
- C) Colon (:)
- D) Pipe (|)

**6. Which command would you use to add a new user named 'davidli' to the system?**

- A) sudo adduser davidli
- B) sudo useradd davidli
- C) sudo newuser davidli
- D) sudo createuser davidli

**7. What does the command 'su – David' allow a user to do?**

- A) Delete the user David
- B) Modify David's permissions
- C) Access the system as the user David
- D) Change David's password

**8. Which command is used to add a comment (like a full name) to an existing user's profile?**

- A) usermod -c
- B) useradd -c
- C) passwd -c
- D) chfn

**9. How can you add a user to a supplementary group without removing them from their current groups?**

- A) sudo usermod -g groupname username
- B) sudo usermod -aG groupname username
- C) sudo groupadd username groupname
- D) sudo useradd -G groupname username

**10. Which flag is used with 'usermod' to lock a user account?**

- A) -k
- B) -L
- C) -u
- D) -S

**11. To remove a user and their personal files simultaneously, which command should be used?**

- A) sudo userdel username
- B) sudo userdel -f username
- C) sudo userdel -r username
- D) sudo rmuser -all username

**12. Which command creates a new group with a specific Group ID (GID) of 5000?**

- A) sudo groupadd -id 5000 hr
- B) sudo groupadd -g 5000 hr
- C) sudo newgroup -v 5000 hr
- D) sudo groupmod -g 5000 hr

**13. When using 'su' without any options, which account does the system attempt to switch to?**

- A) The current user
- B) The last logged-in user
- C) The root user
- D) The system administrator

**14. What does 'sudo' stand for?**

- A) System User Direct Order
- B) Substitute User Do or Super User Do
- C) Secure User Download Only
- D) Standard User Data Output

**15. What are the three standard types of Linux file permissions?**

- A) Open, Closed, Hidden
- B) Read, Write, Execute
- C) Modify, Delete, Create
- D) Admin, User, Guest

**16. Who is the only person authorized to change the ownership of a file?**

- A) The file's owner
- B) Members of the file's group
- C) The superuser 'root'
- D) Any user with write access

**17. In the 'ls -l' output, the 'other' permission is often referred to by what name?**

- A) Public
- B) World
- C) Universal
- D) Global

**18. What happens if you have write access to a file but do NOT have write permission for the directory it is in?**

- A) You can delete the file but not edit it
- B) You can update the data in the file but cannot delete it
- C) You cannot do anything to the file
- D) You automatically gain directory permissions

**19. What does the numeric permission '777' represent?**

- A) Only the owner has full permissions
- B) The owner and group have full permissions
- C) Everyone can read, write, and execute
- D) The file is locked for everyone

**20. What does the numeric permission '644' signify?**

- A) Owner has R/W, group and others can only read
- B) Owner has full access, others have no access
- C) Everyone has R/W access
- D) Owner and group have R/W, others have no access

