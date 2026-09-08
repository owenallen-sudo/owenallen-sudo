# I hate sudo, obviously
Instead of the bloated sudo I use a fork of opendoas on an artix build. I also use the runit init system because it follows the unix philosophy and limine because it is less bloated than grub. I do everything but browsing from the TTY on my computer, without any multiplexer. I start sway followed by librewolf in a heavily restricted firejail if it requires browsing. It doesn't even have access to my downloads folder. I also use unbound without forwarding because of privacy and security concerns. I am currently also recently giving the penquin a diet of only the drivers I need, down to my RTL8852BE wifi card, all inbuilt without modules because as you can see the penquin is getting really, really fat.

# My main projects
1. owenallen-sudo/ish-bugs for catching bugs and vulnerabilities in global application iSH and patching them (I plan on it being my most active project for quite some time).
2. owenallen-sudo/multi-downloader combining some of the best tools for downloading software in their specific niche for fast downloads and not having to remember each the backend's specific usage.
3. I have other projects but I don't pay as much attention to most of them any longer since I don't need them any longer and there are better alternatives for them such as iwmenu compared to my iwdwifi.

# My security and coding views and ethics
1. Most importantly I like to assume a sandbox doesn't exist if it is proprietary since I can't audit it.
2. I refuse to make code that isn't open-source.
3. I much prefer small, auditable codebases
4. I view "feature-rich" as usually meaning bloated
5. I have several times read over NASA's power of 10 but don't implement it due to impracticality. I like to avoid setjmp, longjmp, goto and recursion though. I'll also soon start doinmg most my compiling c in -Wpedantic mode.
6. I also have fears of proprietary software or firmware containing massive vulnerabilities or backdoors.

# About me and what I'm interested in
I'm an open-source software developer (I am best at low level stuff, architecture and security, I suck at remembering syntax and high-level languages) who works on projects such as owenallen-sudo/ish to fix bugs in ish and owenallen-sudo/multi-downloader for downloading software. I am also very interested in plan9's namespaces, seL4 and LionsOS (especially regarding it's fast IPC communication, and lock free deisgn) and beOS (and haiku) extended attributes and multithreading architecture but have never actually tried any of them. My greatest interests are in kernel and filesystem architectures and I plan on working on them once I am more experienced (whilst still working finding bugs in iSH if iSH isn't completely abandoned by then) but not now.
