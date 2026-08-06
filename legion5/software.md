# Lenovo Legion 5 Software Log
## Current Operating System:
Windows 11
# August 2026 Development
## 7/29/26
- Installed Windows 11 on 512gb Inland SSD.
  - Needed Windows 11 for Adobe software, used 32gb USB with Windows Media Creation Tool (seems to be the only way I can get a working ISO burnt on a USB to overwrite a Linux distro.)
  - Was daily driving Kali Linux without doing proper research on why it's impractical to run as a daily driver, we learn, we move on.
    - Listen, just because Mr. Robot runs Kali almost every time he's on a PC does not mean its intended as a daily driver. It's actually funny because I'm pretty sure Elliot daily drives Linux Mint. I guarantee you thousands of people have started networking just because of that show. Shoutout Mr. Robot.
- Performed two more fresh installs due Adobe software error 217 making me think a custom Windows de-bloater was at fault for failed Adobe Lightroom installs. Turns out I was just installing the wrong version of Lightroom.
## 8/5/26
- Attempted to install Fedora Workstation 44, however kept getting error that EFI boot partition was too small (>500mb.)
- Booted to Medicat and used gparted to edit EFI partition and expand it to 600m, had to delete 16gb NFTS partition to do so.
  - This bricked the Legion 5 with Windows unable to boot.
- Performed clean install of Linux Mint to erase all data on NVME drive.
  - Didn't want to give up on installing fedora though, so I used Mint to install Fedora 44 w/ Cinnamon desktop.
- Used Fedora Media Writer to format new Fedora 44 ISO onto spare flash.
- Successfully installed Fedora 44 w/ Cinnamon onto Lenovo Legion 5.
- Tomorrow will use the other half of NVME drive to install Windows 11.
