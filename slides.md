---
theme: apple-basic
highlighter: shiki
lineNumbers: true
title: EoY 2025
info: |
  ## EoY 2025
  End of Year presentation of my life in 2025.
drawings:
  persist: false
mdc: true
transition: slide-left

layout: intro
---

# EoY 2025

End of Year presentation of my life in 2025.

<div class="absolute bottom-10">
  <span class="font-700">
    Sebastian Di Luzio, 2025
  </span>
</div>

<div class="absolute bottom-10 right-10">
  <span class="font-700 text-3">
    Did I mention it's about 2025?
  </span>
</div>

---
transition: slide-up
layout: statement
---

# I played games

---
layout: intro-image-right
image: '/2025/images/genres.png'
transition: slide-up
---

# Genres

Looks like I like soulslikes.

---
layout: 3-images
imageLeft: '/2025/images/New World.png'
imageTopRight: '/2025/images/throne and liberty.png'
imageBottomRight: '/2025/images/Black Desert.png'
transition: slide-up
---

---
layout: 3-images
imageLeft: '/2025/images/afk journey.jpg'
imageTopRight: '/2025/images/Zenless Zone Zero.png'
imageBottomRight: '/2025/images/Honkai Star Rail.png' 
transition: slide-up
---

---
layout: 3-images
imageLeft: '/2025/images/Nioh - coop.png'
imageTopRight: '/2025/images/Borderlands 2.png'
imageBottomRight: '/2025/images/Nioh - thicc.png'
transition: slide-up
---

---
layout: 3-images
imageLeft: '/2025/images/Tiny Tinas Wonderlands - Nico.png'
imageTopRight: '/2025/images/Tiny Tinas Wonderlands - blue.png'
imageBottomRight: '/2025/images/Tiny Tinas Wonderlands - purple.png'
transition: slide-up
---

---
layout: 3-images
imageLeft: '/2025/images/Lies of P - inside.png'
imageTopRight: '/2025/images/Lies of P - beginning.png'
imageBottomRight: '/2025/images/Lies of P - castle.png'
transition: slide-up
---

---
layout: 3-images
imageLeft: '/2025/images/Elden Ring - water.png'
imageTopRight: '/2025/images/Elden Ring - golden.png'
imageBottomRight: '/2025/images/Elden Ring - moon.png'
transition: slide-up
---

---
transition: slide-up
layout: intro-image-right
image: '/2025/images/Elden Ring - veil.png'
---

# Elden Ring (Shadow of the Erdtree)

I will always come back to this, and it is a master piece.

# 5/5

This is an objective fact, not an opinion.

(actually didn't finish the DLC. needed to play baldurs gate)

---
layout: 3-images
imageLeft: '/2025/images/Baldurs Gate 3 - astarion.png'
imageTopRight: '/2025/images/Baldurs Gate 3 - harem.png'
imageBottomRight: '/2025/images/Baldurs Gate 3 - will and shadowheart.png'
---

---
layout: statement
transition: slide-up
---

# I went to league events
For some reason

---
layout: 3-images
imageLeft: '/2025/images/worlds.jpg'
imageTopRight: '/2025/images/lec 2.jpg'
imageBottomRight: '/2025/images/lec 1.jpg'
---

---
layout: intro-image-right
image: '/2025/images/gamescom tencent.jpg'
transition: slide-up
---

# Went to Gamescom

As rosalina

---
layout: 3-images
imageLeft: '/2025/images/gamescom minecraft.jpg'
imageTopRight: '/2025/images/gamescom zzz.jpg'
imageBottomRight: '/2025/images/gamescom witcher.jpg'
---

---
layout: statement
transition: slide-up
---

# Sideprojects
## and similar things

---
layout: intro-image-right
image: '/2025/images/cluster.jpg'
transition: slide-up
---

# The Home Cluster

It's kubernetes running at home.

## State:
- email support! (e.g. jellyfin newsletter)
- we have about 98% uptime :(
- full migration to immich
- remote backups!


---
layout: intro-image-right
image: '/2025/images/cats under screen.jpg'
transition: slide-up
---

# We got cats

They help

---
layout: 3-images
imageLeft: '/2025/images/cats gaming.jpg'
imageTopRight: '/2025/images/cats eldenring.jpeg'
imageBottomRight: '/2025/images/cats chonk.jpg'
---

---
layout: intro-image-right
image: '/2025/images/contributions.png'
transition: slide-up
---

## I also wrote code

So, here's a quick interlude with:

# My open source highlights

---
layout: intro-image-right
image: '/2025/images/github.png'
transition: slide-up
---

# GitHub

I probably spent too much time on here

---
layout: intro-image-right
image: '/2025/images/mage.png'
transition: slide-up
---

# Created container images for mage

I hate java and they STILL haven't merged my PR.

---
layout: intro-image-right
image: '/2025/images/gleam.png'
transition: slide-up
---

# Learned a bit of gleam

It's a fun, strongly typed functional language.

I did a few of the advent of code 2025 challenges on it.

---
layout: intro-image-right
image: '/2025/images/celeryband.png'
---

# Started celery.band

Will be a selfhostable salaryband platform with strong anonymization and simple configuration.


---
layout: intro
transition: slide-up
---

# Back to my sideprojects

---
layout: intro-image-right
image: '/2025/images/iutech.jpeg'
transition: slide-up
---


# Held a talk about my game

At the company internal "IU Tech" conference in Berlin.

---
layout: intro-image-right
image: '/2025/images/diluzio.png'
---

# diluz.io

My personal website.

## State:
- Did a redesign, again.
- Now also includes a CV pdf download


---
layout: statement
transition: slide-up
---

# nix

---
layout: intro-image-right
image: '/2025/images/nix.png'
transition: slide-up
---

# what is nix even
here's a helpful chart

---
layout: center
transition: slide-up
---

# How is software being provided today?

- binaries (.exe, .dmg, .apk, .deb, .rpm, etc.) are built and distributed to end users
- every system needs its own build of the software (windows, mac, linux (debian, arch, ...), etc )
- dependencies are often shared system-wide: software is often not guaranteed to run unless you install other software first

---
layout: center
transition: slide-up
---

# What if
Instead of distributing pre-built binaries, we distributed **build instructions** that anyone can use to build the software from source code in a reproducible way for their specific machine?

---
layout: center
transition: slide-up
---

# Let's take discord as an example



---
layout: center
transition: slide-up
---

# But building everything from source is slow

What if we had a **shared cache** of pre-built packages that anyone can use to download pre-built binaries for their specific machine, and have systems to verify the integrity of the binaries?

---
layout: center
transition: slide-up
---

# Nix is a package manager that does both of these things

It originated in 2003 as a research project by Eelco Dolstra at Utrecht University, and his 2006 doctoral thesis, **The Purely Functional Software Deployment Model**, describes a declarative and functional approach to software deployment and lays out the design of the Nix package manager. ([wikipedia](https://en.wikipedia.org/wiki/NixOS))

---
layout: two-cols-header
---

# Follow me for more

::left::

## <mdi-mastodon class="text-6" /> @maybeanerd@bumscode.com
## <mdi-github class="text-6" /> maybeanerd
## <mdi-web class="text-6" /> diluz.io/sebastian
## <mdi-linkedin class="text-6" /> sebastian-di-luzio

::right::

## <mdi-email class="text-6" /> give-me-feedback-on-the-end-of-year-aka-eoy-presentation-of-the-year-2025-please@diluz.io