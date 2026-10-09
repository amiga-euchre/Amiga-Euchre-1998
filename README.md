# Euchre! — The Card Game for the Amiga (1998)

*Found in a drawer under some moldy socks and half a Zagnut bar.*

**Come on in—let me show you how I built this.**

---

## Overview

**Euchre!** is a single-player euchre game for the Commodore Amiga, originally developed by Rick Keller (that's me!) and released through Aminet in 1998. It was created as a personal hobby project under the publishing name **Bargain Basement Software**.

This repository was created in 2026 to preserve the complete software project—not only the released source code, but also the design documents, development notes, beta archives, artwork, correspondence, and other artifacts that survived from development between 1997 and 1998.

This repository documents not only the finished application, but the process of learning, experimenting, and occasionally stumbling into good ideas that produced it.

---

## About the Project

Development began in 1997 and continued through multiple beta releases before the public Aminet release in 1998.

The project was written in C for AmigaOS using a native Amiga development environment consisting primarily of:

- GoldED
- SAS/C
- GadToolsBox
- Personal Paint

The completed game includes:

- Computer-controlled opponents
- Multiple AI play styles
- Native Amiga graphical interface
- Configurable gameplay options
- Built-in debugging and diagnostic features used during AI development

The computer players are based on heuristic decision-making rather than exhaustive search or card simulation. Their strategy evolved through repeated play-testing, incremental refinement, and practical euchre experience accumulated over years of playing the game.

---

## Preservation Philosophy

The purpose of this repository is historical preservation.

Everything here has been left untouched—spelling, grammar, comments, and code that seemed like a good idea at the time. You name it, it's still here. This is the original stuff; nothing has been prettied up for this repository.

Modern additions—including documentation, Git metadata, and build guidance—have been clearly separated from the historical project.

The goal is to show how yours truly, armed with some high school BASIC, a semester of college FORTRAN, and a few books whose names are lost to time, learned just enough C to be dangerous and create a playable (some say enjoyable) euchre game for the Commodore Amiga.

---

## Why This Repository Exists

I wasn't planning to preserve any of this. I simply never threw it away.

I was looking through some old files on a backup hard drive and found this gold mine of original development history. I've run across references to my old game throughout the years on YouTube and Amiga gaming sites, and when I found this I thought someone might find it interesting.

In addition to the released application, the repository includes much of the original development history:

- Development notes
- TODO lists
- Known bug lists
- Beta archives
- User correspondence
- Interface mockups
- Original artwork
- Revision histories
- Release documentation

---

## Original Release

|                      |                                                      |
| -------------------- | ---------------------------------------------------- |
| **Project**          | Euchre!                                              |
| **Developer**        | Rick Keller                                          |
| **Publishing Name**  | Bargain Basement Software (personal publishing name) |
| **Platform**         | Commodore Amiga                                      |
| **Original Release** | 1998                                                 |
| **Distribution**     | Aminet                                               |
| **Language**         | C                                                    |

---

## Repository Goals

This repository exists to:

- Preserve the original source code.
- Preserve the original artwork and project assets.
- Preserve the original documentation.
- Document the software architecture.
- Document the AI design and evolution.
- Record the project's development history.
- Document the original build environment.
- Enable future developers to understand, rebuild, and study the project.

Historical accuracy takes precedence over modernization.

---

## Repository Layout

```text
docs/          Historical documentation
source/        Original source code
assets/        Graphics, artwork, and project resources
reference/     Manuals and technical references
tools/         Original and preservation utilities
```

Additional directories contain preserved development artifacts such as beta releases, design concepts, screenshots, and correspondence.

---

## Building

The preferred method of building the software is to recreate the original Amiga development environment using emulation.

Documentation describing the original development tools, build process, and development environment is provided in the `docs` directory.

---

## Historical Notes

The Git history begins with the preservation effort undertaken in 2026. All files and documents are original. Nothing has been rewritten or recreated. What you see is what I wrote 30 years ago (-ish).

While revisiting this project, it became apparent that the development process itself might be just as interesting as the finished game. It was a process of gradual discovery of a way to code a (to me) fairly large project in such a way as to be maintainable and approachable. The way to eat an elephant is one bite at a time.

> It's not about preserving a game.
>
> It's about preserving the creative process behind it.

---

## Future Development

This repository preserves the original project. That is its sole purpose.

I haven't written a line of code since I put this project away in the '90s. Revisiting it has been a lot of fun. I remember spending nights experimenting, debugging, and trying to learn how to do the next thing. Now that I finally have some free time, I thought I might revisit it. Perhaps a new and more modern version, capable of running on multiple platforms—including the newly released retro Amigas (now wouldn't that be cool?).

That project—if it happens—will live in a separate repository, and I'll link it here.

---

If you're here because you played **Euchre!** back in the day, welcome back.

If you're here because you're interested in how software was built by a solo developer before Git, Stack Overflow, and search engines answered every programming question, I hope you find something worthwhile here.

Either way, thanks for stopping by.
