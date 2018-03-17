# platform-pine64

Kernel Source: https://github.com/ayufan-pine64/linux-pine64.git, branch: pine64-hacks-1.2 (3.10.105)

This repo contains all platform-specific files, used by the Volumio Builder to create a **Pine64** image:

- Kernel files (kernel, modules, firmware)
- Other files, e.g. used during the boot process
- a script used for compiling the kernel & modules (you may need to adapt repo settings)
- a script used to compile u-boot and everything needed to prepare this.
- a script used to compile the pine models dtb files
  (Thanks to longsleep and ayufan for their excellent work on the pine64 platforms)  

**Platform files, kernel version 3.10.104**
- 20161105: Full volumio support
- 20161106: Improved audio jack mixer settings, added sndhdmi
- 20161107: Returning to longsleep's default for hdmi audio (built-in)
- 20161121: Adding iso8859-1 as a built-in module
- 20170331: Adding snd-aloop to support brutefir
- 20170415: Enabling A64 DAUDIO and SPDIF  
- 20171106: Fixed an initrd load issue  

**Platform files, kernel version 3.10.105-bsp-1.2+**
- 20171110: Switched to kernel 3.10.105, enabled support for sopine64 & pine64 LTS incl. eMMC boot  


