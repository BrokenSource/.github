> [!NOTE]
> _This file is shared across the organization, it might not apply for all repositories._

Hi, and thanks for your interest in contributing to the project!


# Areas


## ❤️ Funding

> Open Source sustainablity.

Support the project financially, consider becoming a sponsor or making a donation, every little bit helps!

I would heartwarmingly do this all for free, but the society we live in works on numbers.


## 🟢 Sharing

> Words on the street matter!

**Best way** to contribute, spread the word, add attributions on derivative work.

So far, I've spent zero resources on marketing but minor, non-intrusive self-promotion when applicable. If any of the projects helped you, and/or would help others as you see fit, consider sharing it around!

- I'm mostly [away](https://x.com/GrianMC/status/1143807515454558208) from social media, even so, perfectionism _blocks me_ from shameless promotions.
- A simple post or mention can go a long way in helping others discover the project!


## 🔵 Documentation

> Talk is cheap, show me the code!

**Help needed**, I'm often on limited time to write structured documentation.

My focus is always on the code's engineering, structure and developer experience. While I type hint everything and organize in a way that looks _"readable"_ to me, not everyone may find it intuitive or read the code to learn or when in doubt.

- Use `uv run --project {name} mkdocs serve` within the monorepo to preview docs, edit, live changes.
- You can improve or propose new `examples/*.py` scripts to showcase project usage.


## 🔴 Issues, Feedback

> New perspectives requires fresh eyes!

**Simple way** to contribute. I can only test the code so much and have new ideas.

Feel free to reach out if you have any questions or need clarifications, preferably in a public GitHub Issues or Discussions, so that other users can benefit from the knowledge, instead of unindexable chats.

- All repositories contains comprehensible issues templates, don't hesitate to use them.
- Not all ideas follows the project's scope, so please be mindful of that.


## 🟡 Code

> Too many moving parts and complexity.

**Not ideal**, it's better to report issues, show findings or ideas so I implement them directly.

Think of the projects as something that _happen to be splittable into well-defined packages_ from a collection of personal tools over the years. I'm very picky about the structure and organization of the code, the shape matters a lot to me, so I'm able to make quick progress after finished ideas.

Complications:
- There are _a lot_ of moving parts and complexity in the codebase as a whole (in general), with deep advanced++ usage of python and packages, math, platforms, and years of implicit experience.
- Fair to say, I expect to maintain full rights on the codebase as a BDFL - only _huge contributions_ would have significant impact given the existing codebase, which took years to develop on my own.
    - Consider all submitted code's rights to be retained by the project author.
    - Call me out if I ever diverge, and I'll make it right.
- Most fixes are negligible or trivial, but they may have deeper consequences.
- I'm doing fine progress-wise, code isn't about rushing features.

That isn't to say I am not open to code contributions, please talk to me first!


# Setup

Getting a local development environment:

- Fork the related project in which you intend to contribute
- Clone the monorepo [BrokenSource](https://github.com/BrokenSource/BrokenSource), with all submodules, and dependencies (`uv`, `git`):
    - **Standard**: `git clone --recurse-submodules https://github.com/BrokenSource/BrokenSource`, or:
    - **Linux/MacOS**: `/bin/bash -c "$(curl -sS https://brokensrc.dev/get.sh)"`
    - **Windows**: `irm https://brokensrc.dev/get.ps1 | iex`
- On the root of
    - Add remote: `git remote add https://github.com/<YourUsername>/<Fork>`
    - Sync with upstream: `git fetch origin && git rebase origin/main`
- Make changes, commit, send pull requests.

> [!WARNING]
> Some changes might have multiple repositories involved, in which case please mention the related pull requests down the dependency chain.
