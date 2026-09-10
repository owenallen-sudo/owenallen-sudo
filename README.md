# I hate sudo, obviously
(Yes, I know my username is owenallen-sudo. The irony is intentional.)
Instead of the bloated sudo, I use a fork of opendoas on an Artix build... Visit my MYSETUP.md if interested in my setup. Also visit ABOUTME.md if curoius about my interests. Please visit WHY-GITHUB-IS-BAD.md even if you don't feel interested.

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

**Note:** I have other projects not mentioned but maintain them less actively because superior or more active alternatives exist (e.g., iwmenu vs. my iwdwifi).

# Contributions
- I would love it for people to audit my codebases, especially with AI so I can keep my code clean, free of bloat and free of bugs. Particularly in ish-bugs.
- If you have a mac and an iPhone please do dynamic analysis and testing of ish-bugs since I don't have a mac and therefore can't sideload my own changes.
