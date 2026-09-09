# I hate sudo, obviously
(Yes, I know my username is owenallen-sudo. The irony is intentional.)
Instead of the bloated sudo, I use a fork of opendoas on an Artix build... Visit the bottom of this README under the 'My Setup' section if interested in my setup.

# My ish-bugs project
- ish-bugs is by a large margin my most active and most recent project focusing on fixing major vulnerabilities and bugs in iSH (an x86 alpine emulator on iOS) as well as just cleaning the codebase.
- Contrasting with popular opinion in iSH developers communities I like to view proprietary sandboxes (including the one in iOS) as non-existent since I can't audit them.
- I also add error codes in the situation of a crash to prevent silent failures.

## What I've fixed and focus most on
- I focus on resource leaks a lot since they eat resources, make the system unstable and ruin security.
- I also focus a lot on integer overflow/underflows, buffer overflow/underflows and null pointer dereferences a lot simply they are such major vulnerabilities.
## PRs
- Despite contrasts in philosophy I still attempt PRs because who realistically is going to put down a security fix.

# My multi-downloader project
- multi-downloader combines some of the best tools (such as surge, git, wget for finding filenames before something else downloads the actual files when downloading a whole directory and many more) for downloading software in their specific niche for fast downloads and so I don't have to remember each tool's specific usage.
- It hasn't been given much modifications recently because it works well for me and so far as I know it has no issues or bugs. Don't get me wrong, this project isn't abandoned, it just works so I don't want to bloat it.

**Note:** I have other projects not mentioned but maintain them less actively because superior or more active alternatives exist (e.g., iwmenu vs. iwdwifi).

# My security and coding views and ethics
- I refuse to make code that isn't open-source.
- I much prefer small, auditable codebases over "feature-rich" (bloated) alternatives
- I have several times read over NASA's power of 10 but don't implement it due to impracticality. I like to avoid setjmp, longjmp, goto and recursion though. I'll also soon start doing most my compiling c in -Wpedantic mode.

# Contributions
- I would love it for people to audit my codebases, especially with AI so I can keep my code clean, free of bloat and free of bugs. Particularly in ish-bugs.
- If you have a mac and an iPhone please do dynamic analysis and testing of ish-bugs since I don't have a mac and therefore can't sideload my own changes.

# About me and what I'm interested in
- Self-taught open-source developer, strongest in low-level systems, architecture, and security. Weak with syntax, abstractions, and high-level languages (I can't even write a web app, low-level is just more intuitive somehow).
-  I only work on projects with purpose.
-  I am open to AI but also have concerns with it.
-  ps: Never ask me to code in HTML, CSS, JS and probably not in python because it won't go well. It needs to be lower level.
-  I am very interested in Plan9's namespaces, seL4 and LionsOS (especially regarding its fast IPC communication, and lock free design) and beOS (and haiku) extended attributes and multithreading architecture but have never actually tried any of them, it is just curiosity in the architecture for now.
-  My greatest interests are in kernel and filesystem architectures but that is just curiosity for now.

# My setup
- **My OS** I use a manual artix base build
- **Root access:** fork of opendoas
- **Init system:** runit (clean and follows the Unix philosophy)
- **Bootloader:** Limine (less bloated than GRUB)
- **Workflow:** TTY for everything; Sway WM + LibreWolf in Firejail (access to nothing but its own profile) only when browsing
- **DNS:** Unbound without forwarding (privacy/security)
- **The penguin's diet:** Will soon be custom-built with only essential drivers (RTL8852BE, built-in—no modules) because of how fat the penguin is getting.
