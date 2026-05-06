# Open Source Contribution — Community Discussion Notes

**Date:** Saturday, 2 May 2026
**Time:** 6:00 PM – 8:00 PM IST
**Format:** Community discussion / open chat

---

## Overview

A wide-ranging community discussion that started with how beginners can get into open source contribution, and expanded into the broader philosophy, culture, and ecosystem around open contribution — beyond just writing code.

---

## Getting Started: A Path for Beginners

The conversation opened with a practical question: how does someone with little or no open source experience take their first steps?

The consensus was to start with projects or tools you already use and care about. Familiarity lowers the barrier to entry — you already understand what the tool is supposed to do, and you're more likely to notice when something is wrong.

A concrete beginner-friendly path that came up: don't rush to write code. Instead, start by:

1. Reading existing issues on the project tracker
2. Trying to **reproduce bugs** yourself
3. Understanding *how* and *why* the issue happens
4. Leaving **useful, technical comments** on existing bug reports — even if you don't fix anything yet

This kind of engagement teaches you how the project works, signals your interest to maintainers, and contributes real value to the community's understanding of the problem.

**Good first issues** (usually tagged as such on GitHub and GitLab) are a well-known entry point, but the group noted that the quality of these labels varies widely across projects.

---

## Non-Code Contributions

A major theme was that open source needs far more than programmers. The group explored several categories:

### Documentation and Translation

- Translating documentation makes software accessible to non-English-speaking communities
- Examples: **Debian** software localization, **Node.js** documentation translations
- Translation work requires language skill, not programming skill — a huge and underappreciated contribution path

### Open Data

Contributing to open datasets is a form of open contribution that many people overlook:

- **OpenStreetMap** — community-maintained map data; discussed in detail below
- **Open Food Facts** — open database of food products and nutritional information
- **Wikimedia / Wikipedia** — the most well-known open knowledge project

### Open Hardware–Adjacent Software

Since hardware itself is hard to collaborate on through Git-style workflows (you can't send someone a pull request for a PCB), contributions in this space often happen in the surrounding software ecosystem — firmware, drivers, tooling, robotics middleware:

- **FreeRTOS** and **Zephyr** — real-time operating systems
- **ROS (Robot Operating System)** — robotics software framework
- **QMK** — keyboard firmware (popular entry point for embedded newcomers)
- **Linux drivers** — a well-established path for systems programmers
- **Mesa graphics drivers** — open-source GPU driver stack

### Design

One of the stronger points raised was that **design contribution pipelines are broken in most open source projects**. Many designers have ideas, SVGs, mockups, and UX feedback — but have nowhere to put them. Unlike code, where pull requests are a well-understood workflow, design contributions lack a clear acceptance process in most projects. This is a gap worth addressing.

### Advocacy, Licensing, and Community Education

- Helping people understand open licenses (MIT, GPL, Apache, Creative Commons, etc.)
- Speaking at meetups, writing blog posts, running workshops
- Explaining what you've learned — sharing knowledge is contribution

---

## OpenStreetMap Deep Dive

OpenStreetMap (OSM) got specific attention as an example of open data contribution done well.

Two tools came up:

- **OSMAnd** and the **OSM web editor** — for deeper mapping work; more powerful but also more complex
- **StreetComplete** — described as the more beginner-friendly option; it gamifies the contribution experience by asking simple, focused questions: *Is this road paved or unpaved? What are the opening hours of this shop? Does this path have steps?* Users answer questions based on what they observe around them, and the answers feed directly into the OSM dataset

StreetComplete is a great example of lowering the contribution barrier through good UX design — something many open source projects could learn from.

---

## Foundations, Governance, and Legal Structures

The discussion covered how open source projects gain long-term stability through foundations and formal governance:

- **Linux Foundation**
- **Apache Software Foundation** — known for its "community over code" philosophy; the idea that a healthy, self-sustaining community matters more than any particular piece of software
- **Python Software Foundation**
- **Blender Foundation** and **Godot Foundation**
- **CNCF (Cloud Native Computing Foundation)**

Foundations give projects legal identity, fundraising structures, trademark protection, and governance frameworks. They matter especially when a project grows beyond what a single maintainer or company can manage.

---

## Corporate Involvement in Open Source

Many large companies are active contributors to open source — not purely out of altruism, but because they depend on it. Companies contribute to Linux, device drivers, databases, compilers, and infrastructure tools because doing so benefits their own products and operations.

The group noted that many significant open source projects are either maintained by companies (e.g., React/Meta, Kubernetes/Google, VS Code/Microsoft) or supported through foundations. This is neither inherently good nor bad — it reflects the reality that open source is part of the software industry's infrastructure.

---

## Software Freedom and Digital Rights

The conversation touched on the history and philosophy behind free software:

- **Richard Stallman**, **GNU**, **GCC**, **Emacs**
- The origin story of the free software movement, partly rooted in Stallman's frustration over not being able to modify printer firmware
- The four freedoms: to **use**, **modify**, **understand**, and **share** software
- Organizations like **SFLC (Software Freedom Law Center)** and related advocacy groups that work on internet freedom, privacy, software patents, site blocking, and legal advocacy around digital rights

Giri made the point clearly: **open source is a philosophy, not just a category of software licenses**.

---

## Why Contribute? And How to Think About It

Shane pushed back on treating open source contribution as a resume line or a GSoC trophy. The better framing:

- Contribute because you **use the project** and want it to be better
- Contribute to **understand how it works** at a deeper level
- Contribute to **share what you learn** with others in the community

The worst kind of open source contribution is the kind where someone submits a patch they don't understand, just to have a merged PR to point at.

---

## A Practical Story: Contributing to Godot

Giri shared his own experience contributing to the **Godot game engine** as a grounded example of what real contribution looks like:

1. Started by using Godot for a game development project — genuine user first
2. Found a good first issue that matched his interest
3. Had early conversations with maintainers to understand the scope and expectations
4. Implemented a small feature: an animation timeline improvement
5. Opened a pull request and went through review rounds
6. Waited through Godot's feature freeze and release cycle before the PR was merged

The story illustrated that even a small contribution involves: discussion, patience, feedback loops, and understanding the project's release process. It's not just about writing the code.

---

## Informal Second Half: Side Conversations

The last portion of the session became more informal, touching on:

- Open source conferences and events
- Rust, C/C++, compilers, and memory safety
- Windows performance observations
- **AI coding tools** (Claude, Codex, etc.) and their role in development workflows
- Token costs and the economics of AI-assisted development
- A cautionary note on AI-generated open source contributions: if a contributor doesn't understand the code, the review burden falls entirely on maintainers, and shallow contributions can do more harm than good

---

## Key Takeaways

Open source contribution is not about writing code. It's about:

- **Using** projects and understanding them deeply
- **Reading issues**, reproducing bugs, and adding useful context
- **Translating**, mapping, designing, documenting, advocating
- **Understanding the community** — how decisions are made, how releases work, what maintainers need
- **Sharing what you learn** — in blog posts, talks, comments, or conversations like this one

The best contributions come from genuine engagement with the project's problems and people — not from chasing merged PRs.

---

*Notes compiled from community discussion. Participants included Shane, Giri, and others.*

1. pepy.tech (Python package download stats and popularity tracker)
   https://pepy.tech/search?q=tensorflow

2. contribute to blender (official guide to contribute to Blender open-source project)
   https://www.blender.org/get-involved/

3. open Street Map (open-source collaborative world map project)

4. rizi (reverse engineering framework similar to radare2)
   https://rizin.re/

5. sflc (legal support organization for free and open-source software)
   https://sflc.in/

6. Osm (OpenStreetMap ecosystem and tools for mapping)

7. Streetcomplete (Android app to contribute to OpenStreetMap easily)
   https://wiki.openstreetmap.org/wiki/StreetComplete

8. apache software foundation (major open-source foundation behind Apache projects)
   https://www.apache.org/

9. Rust Book (official Rust programming language documentation and guide)
   https://doc.rust-lang.org/book/

10. visual c++ sucks (discussion/opinion on limitations of MSVC toolchain)

11. uber ai issues budget issues (discussion on scaling challenges and cost issues in AI systems)

12. krita (open-source digital painting and illustration software)
    https://apps.kde.org/en-gb/krita/

13. apache (official Apache organization site)
    https://www.apache.org/

14. tldr-pages (community-driven simplified man pages for CLI tools)
    https://github.com/tldr-pages/tldr

15. debian orphaned packages (list of unmaintained Debian packages needing contributors)
    https://www.debian.org/devel/wnpp/orphaned

16. openSUSE junior jobs (beginner-friendly contribution tasks for openSUSE)
    https://en.opensuse.org/openSUSE:Junior_jobs

17. nix contribution guide (how to contribute to Nix ecosystem)
    https://nix.dev/contributing/how-to-contribute.html

18. rizin (reverse engineering framework and toolkit)
    https://rizin.re/

19. lkml (Linux Kernel Mailing List for kernel development discussions)
    https://lkml.org/

20. codeberg (Git hosting platform focused on open-source and privacy)
    https://codeberg.org/

21. mattermost (open-source team communication and collaboration platform)
    https://mattermost.com/

22. sflc (Software Freedom Law Center India)
    https://sflc.in/

credits  Som , Rajveer, Giri, Navin, Akash, Hari Thankyou for sharing your knowledge and experience in the Discussion
