# I hate sudo, obviously
(Yes, I know my username is owenallen-sudo. The irony is intentional.)
Instead of the bloated sudo, I use a fork of opendoas on an Artix build... Visit my MYSETUP.md if interested in my setup.

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
- Self-taught open-source developer, strongest in low-level systems, architecture, and security. Weak with syntax, abstractions, and high-level languages (I can't even write a web app, low-level is just more intuitive somehow). ps: Never ask me to program in HTML, CSS, JS and probably not python; it won't go well, they're too high level for me. Also if you ask me to fix a memory leak without looking up syntax I'll struggle (I'd even rather see i = i + 1 if possible to i++).
-  I only work on projects with purpose.
-  I am open to AI but also have concerns with it.
-  I am very interested in Plan9's namespaces, seL4 and LionsOS (especially regarding its fast IPC communication, and lock free design) and beOS (and haiku) extended attributes and multithreading architecture but have never actually tried any of them, it is just curiosity in the architecture for now.
-  My greatest interests are in kernel and filesystem architectures but that is just curiosity for now.

**Please Read** This project is currently hosted on GitHub.  This is not ideal; GitHub is a
proprietary, trade-secret system that is not Free and Open Souce Software
(FOSS).  I am deeply concerned about using a proprietary system like GitHub
to develop my FOSS projects. I rely on AI though so don't want to use codeberg (because of their ban on AI) and don't want to self-host because my wifi is terrible and it will be a major issue for people visiting my projects and as a result I am looking for other alternatives. I urge you to read about the
[Give up GitHub](https://GiveUpGitHub.org) campaign from
[the Software Freedom Conservancy](https://sfconservancy.org) or https://www.howtogeek.com/why-developers-are-ditching-github-for-codeberg-and-self-hosting-alternatives/ for a quick overview to understand
some of the reasons why GitHub is not a good place to host FOSS projects. I also encourage you to read https://www.gnu.org/software/repo-criteria-evaluation.html for more alternatives to GitHub. But most of all, just spread the word, on social media, whatever you like! When I move to an alternative I will likely keep GitHub as a maintained mirror at first then fade it out and eventually stop maintaining the GitHub mirror, whilst keeping links in this README to the maintained projects on alternative platforms.
