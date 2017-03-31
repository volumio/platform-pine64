# platform-pine64

Kernel Source: https://github.com/longsleep/linux-pine64.git, branch: pine64-hacks-1.2 (3.10.104)

This repo contains all platform-specific files, used by the Volumio Builder to create a **Pine64** image:

- Kernel files (kernel, modules, firmware)
- Other files, e.g. used during the boot process
- a script used for compiling the kernel & modules (you may need to adapt repo settings)
- a script used to compile u-boot and everything needed to prepare this.
  (Thanks to longsleep for his excellent information at https://github.com/longsleep/build-pine64-image)

**Platform files, kernel version 3.10.104**
- 20161105: Full volumio support
- 20161106: Improved audio jack mixer settings, added sndhdmi
- 20161107: Returning to longsleep's default for hdmi audio (built-in)
- 20161121: Adding iso8859-1 as a built-in module
- 20170331: Adding snd-aloop to support brutefir
