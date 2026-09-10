# Basic facts of my setup
- **My OS** I use a manual artix base build
- **Root access:** opendoas
- **Init system:** runit (clean and follows the Unix philosophy)
- **Bootloader:** Limine (less bloated than GRUB)
- **Workflow:** TTY for everything; Sway WM + LibreWolf in Firejail (access to nothing but its own profile) mainly when browsing
- **DNS:** Unbound without forwarding (privacy/security), check UNBOUND.md for my configuration

# The penquins upcoming diet
- Linux kernel 7.2.2
- Linux will be compiled inbuilt without modules support
- I will compile only the drivers for my hardware, down to the RTL8852BE wifi driver
- No bluetooth or ethernet support; I use wifi and simply don't need bluetooth
- NUMA emulation
- Optimised more for security than performance with performance as a 2nd priority

