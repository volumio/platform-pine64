# platform-pine64

Kernel Source: https://github.com/ayufan-pine64/linux-pine64.git, branch: pine64-hacks-1.2 (3.10.105)
Kernel Source: https://github.com/gkkpch/linux-mainline.git, branch linux-5.7.y


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

**Platform files, kernel version 5.7.19**
- 20201203: Major update, moved to kernel 5.7.19
- 20201203: Pine64/plus not supported yet (planned)
- 20201203: known issue: rtl8723-bt not supported
- 20201203: preparing for pine64/pine64plus
- 20201204: fix default headphone from "off" to "on"
- 20201208: Add wifi support for Pine64 module (rtl8723bs)/
Folder rename and contents restructure
- 20201209: Enable pine64/pine64plus/ enable eMMC boot for soPine64/Pine64LTS
- 20201222: Add I2S/HDMI/SPDIF to Pine64/Pine64+
- 20210114: Preparing for Volumio Buster (slight renaming of items)
- 20220106: Boot params: change name from uEnv.txt.pine64 to uEnv.txt.pine64base









