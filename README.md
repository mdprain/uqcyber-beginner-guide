# UQ Cyber Squad Beginner's Guide to Ethical Hacking

So you want to get started in ethical hacking, but don't exactly know where to begin? This guide will provide links to excellent resources to get you started! But before you begin, it's important to have the tools ready to go to start learning.

## DISCLAIMER

Please remember, **NEVER ATTEMPT ANY OF KIND OF HACKING ON COMPUTERS YOU DO NOT OWN.** That's why platforms like Hack The Box exist. **You have been warned!**

## Required Tools

The first thing you want to have is some form of a Linux distribution (or "distro") ready to use. Almost all of your hacking time will be spent in the Linux environment, so it's mandatory to have.

*If you're already running some form of Linux in your method of choosing, then you're all set! Skip to the "Recommended Resources" section below*

There are many ways to go about this - a popular way is to use a virtual machine (VM) to install a hacking Linux distro on. This is probably the easiest option for beginners as it is fairly easy to setup, and doesn't require replacing your main operating system. The obvious downside is that since you're working in a VM, you won't be getting the "bare metal" speeds you would if you were to run Linux natively. This usually isn't a problem since most of the tools don't require a huge amount of CPU/GPU power (with the exception of password cracking). But if running in a VM is too slow for you, an alternate solution is to create a bootable USB drive with the Linux distro on it and boot into that when required.

Another option is to replace your main operating system (or dual boot) with a more common and user-friendly version of Linux, and install the tools as needed. This is a good way to force yourself to become familiar with Linux, plus most of tools are easily acquired through your distro's package manager. One downside is that not every tool is up to date (or even available) but thankfully nearly everything can be manually downloaded and compiled through GitHub, so this is not a huge problem.

### Recommended Security Distributions

- **Kali Linux** - https://www.kali.org/ - The most popular distro for hacking, with all the neccessary tools you need to get started. This option is only suited for a VM or a bootable USB drive, and not as your main OS.
- **Parrot** - https://www.parrotsec.org/ - A slightly newer security-focused distro which is a good alternative to Kali. The Home edition is especially great if you want to install it as your main OS with the benefit of easily accessable tools.

### Recommended Beginner Distributions

- **Ubuntu** - https://ubuntu.com/ - Originally the most popular Linux distro, and probably still the most well known of them all. Very user friendly, and most tools are available through the "apt" package manager. If you're coming from a Mac OS background, this is a good choice for familiarity.
- **Linux Mint** - https://linuxmint.com/ - This is the new champion of beginner-friendly distros, but in reality it's just a special version of Ubuntu with some tweaks and additions. If you're coming from a Windows background, this is an excellent choice.

*NOTE: There are thousands of more distributions to discover, and even more opinions on which is best to use, but I'm only listing the ones that have always been highly recommended.*

Once you have Linux set up and running, you're ready to start hacking!

## Recommended Resources

### Learning

- **TryHackMe *(Easy)*** - https://tryhackme.com/ - The first resource that I recommend to people starting out, especially if you're not familiar with all computer terminology. There are many great paths to choose from, like "Pre-Security" and "Complete Beginner" which will guide you through the basics of nearly everything to do with computer security. I cannot recommend this one enough!
- **Hack The Box Academy *(Easy/Medium)*** - https://academy.hackthebox.com/ - This is another great one for beginners, with a heap of free "Fundamental" modules to go through. There is a little less hand-holding than TryHackMe, but this can be beneficial to get into the mindset of "trying harder" when solving problems and challenges.
- **OverTheWire: Wargames *(Easy/Medium)*** - https://overthewire.org/wargames/ - If you're struggling to get a hang of all the Linux commands, the "Bandit" wargame challenges are a great way to learn all the key ones. There is no hand-holding in this one, so be warned!

### Practice

- **Hack The Box *(Medium/Hard)*** - https://www.hackthebox.com/ - The most popular website for practicing your pen-testing skills. No walkthroughs or guides are allowed for the boxes (until they are officially "retired"), so it's best to go through TryHackMe or their own academy website before attempting these. The new "Starting Point" boxes are the best way to start. There is also a "Challenges" section if you want to practice your CTF skills!
- **PicoCTF *(Easy/Medium)*** - https://play.picoctf.org/ - If CTFs are more your thing, this is the best beginner website for a whole bunch of great challenges that range in difficulty from "extremely easy" to "quite challenging".

### YouTube

- **John Hammond** - https://www.youtube.com/c/JohnHammond010 - Great channel on everything cybersecurity and hacking.
- **IppSec** - https://www.youtube.com/channel/UCa6eh7gCkpPo5XXUDfygQQA - Another great channel that's focused on Hack The Box retired machine walkthroughs.

### CTF Checklists

Sometimes, you're going to run out of ideas on what to do when trying to find a flag in a CTF. These following links are great "checklists" to go through whenever you're in that situation!

- **CTF Katana** - https://github.com/JohnHammond/ctf-katana - This is John Hammond's most comprehensive checklist that covers every category you'll find in a CTF.
- **CTF checklist for beginners** - https://fareedfauzi.gitbook.io/ctf-checklist-for-beginner/ - Another checklist which is suited more for beginners, but still very helpful.

## Conclusion

I hope the above information helps you in your cybersecurity journey, and don't forget to "try harder"! :)
