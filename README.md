# I hate sudo, obviously
Instead of the bloated sudo, I use opendoas on an Artix build... Visit my MYSETUP.md if interested in my setup. Also visit ABOUTME.md if curious about my interests. Please visit WHY-GITHUB-IS-BAD.md even if you don't feel interested.

# My ish-bugs project
- ish-bugs is a project focusing on fixing major vulnerabilities and bugs in iSH (an x86 alpine emulator on iOS) as well as just cleaning the codebase.
- Contrasting with popular opinion in iSH developers communities I like to view proprietary sandboxes (including the one in iOS) as non-existent since I can't audit them.
- I also add error codes in the situation of a crash to prevent silent failures.

## What I've fixed and focus most on in ish-bugs
- I focus on resource leaks a lot since they eat resources, make the system unstable and ruin security.
- I also focus a lot on integer overflow/underflows, buffer overflow/underflows and null pointer dereferences a lot simply they are such major vulnerabilities.
## PR plans for ish-bugs
- Despite contrasts in philosophy I plan on PRs because who realistically is going to put down a security fix. I will organise my commits, improve commit details and test my build out (with sidestore or something) and split the PR into multiple smaller ones first (my PR was denied before so I will try all these first).

# My smaller projects
- multi-downloader combines several existing tools for downloading software in their specific niche for fast downloads. Check the subheading below if interested.
- keyd-runit-artix is a runit script to start keyd (an OS-level key remapper) because I realised there is no official package. Despite a very small thing it can make life more convienient.

**Note:** I have other projects not mentioned but maintain them less actively because superior or more active alternatives exist (e.g., iwmenu vs. my iwdwifi).

# My multi-downloader project in more detail:
- multi-downloader combines some of the best tools (such as surge, git, wget for finding filenames before something else downloads the actual files when downloading a whole directory and many more) for downloading software in their specific niche for fast downloads and so I don't have to remember each tool's specific usage. It is recently in a transition to codetrunk (formerly gitbuild)
- It hasn't been given much modifications recently because it works well for me and so far as I know it has no issues or bugs. Don't get me wrong, this project isn't abandoned, it just works so I don't want to bloat it.
# Contributions
- I would love it for people to audit my codebases, especially with AI so I can keep my code clean, free of bloat and free of bugs. Particularly in ish-bugs.
- If you have a mac and an iPhone please do dynamic analysis and testing of ish-bugs since I don't have a mac and therefore can't sideload my own changes.
