LINDX

A hardened, gaming-ready Linux distribution built on Debian, powered by the custom Xamnod kernel.

About

LINDX is an independent Linux distribution built on Debian foundations, with the stock kernel replaced by Xamnod — a custom kernel tuned for responsiveness, security, and gaming workloads. The desktop runs XFCE: fast and configurable rather than heavy. LINDX ships with hardened defaults out of the box, so you're not left assembling a secure system after install.

 
Kernel Xamnod
Base Debian
Desktop XFCE
Focus Security · Gaming
License GPLv3

Features

· Xamnod Kernel — a custom-built kernel tuned for gaming and low-latency response
· XFCE Desktop — lightweight, fast, and fully configurable, no bloat by default
· Security Hardening — sane, hardened defaults active from the very first boot
· Gaming Optimizations — scheduler tweaks and low-latency I/O for smoother gaming
· Debian Base — for stability, compatibility, and speed
· Fully Open Source — released under GPLv3, full source available on GitHub

Download

Free to download, free to modify, free to redistribute.

⚠ All versions below v3.1 are code-only releases without a working build.

Version Status Link
v3.2 Latest working build Download ISO
v3.1 Working build Download ISO
v3.0 Code only View Source
v2.x Code only View Source
v1.0 Early release Download ISO

Build from Source

Extract an existing ISO, or build LINDX from scratch using the automated build script.

Required tools: squashfs-tools xorriso grub-pc-bin grub-efi-amd64-bin mtools live-boot casper git

Extracting files from an ISO

```bash
mkdir -p /tmp/iso-mount
sudo mount -o loop LINDX-v3.iso /tmp/iso-mount

sudo unsquashfs -d squashfs-root /tmp/iso-mount/live/filesystem.squashfs
sudo umount /tmp/iso-mount
```
