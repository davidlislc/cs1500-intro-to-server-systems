# boot process

**1. What is the correct general sequence of the RHEL boot process?**

- A) Power-on → GRUB2 → Kernel → systemd → BIOS/UEFI
- B) Power-on → BIOS/UEFI → GRUB2 → Kernel → initramfs → systemd → User Space
- C) BIOS/UEFI → Power-on → Kernel → initramfs → systemd
- D) Power-on → initramfs → Kernel → GRUB2 → systemd

**2. Which component is responsible for performing the Power-On Self-Test (POST)?**

- A) GRUB2
- B) Kernel
- C) Firmware (BIOS or UEFI)
- D) systemd

**3. What is a primary limitation of the BIOS system compared to UEFI?**

- A) It only supports graphical desktops
- B) It is tied to the Master Boot Record (MBR), which limits disk size to 2TB
- C) It cannot initialize the CPU
- D) It uses the GUID Partition Table (GPT)

**4. Which bootloader is standard for RHEL and where is its main configuration file located?**

- A) LILO; /etc/lilo.conf
- B) systemd; /etc/systemd/system.conf
- C) GRUB2; /boot/grub2/grub.cfg
- D) initramfs; /etc/dracut.conf

**5. What is the role of initramfs in the boot process?**

- A) It replaces the kernel permanently
- B) It provides a temporary root filesystem to load drivers and mount the real root filesystem
- C) It is the first process to run after power-on
- D) It manages the graphical desktop environment

**6. In RHEL, which process replaces the legacy 'init' and is assigned PID 1?**

- A) GRUB2
- B) systemd
- C) Kernel
- D) bash

**7. How does systemd manage different boot states, such as multi-user mode or graphical mode?**

- A) Using MBR partitions
- B) Through BIOS settings
- C) Using 'targets' (e.g., multi-user.target)
- D) By recompressing the kernel

**8. Which partition system does UEFI use to remove the size constraints found in legacy BIOS?**

- A) Master Boot Record (MBR)
- B) Extended Partition
- C) GUID Partition Table (GPT)
- D) Boot Signature (0x55 0xAA)

