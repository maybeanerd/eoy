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
layout: 3-images
imageLeft: '/2025/images/games/animal_well.png'
imageTopRight: '/2025/images/games/baldurs_gate.png'
imageBottomRight: '/2025/images/games/ffxiv.png'
transition: slide-up
---

---
layout: 3-images
imageLeft: '/2025/images/games/borderlands_2.png'
imageTopRight: '/2025/images/games/ghost.png'
imageBottomRight: '/2025/images/games/borderlands_1.png'
transition: slide-up
---

---
layout: 3-images
imageLeft: '/2025/images/games/cyberpunk_2.png'
imageTopRight: '/2025/images/games/cyberpunk_1.png'
imageBottomRight: '/2025/images/games/letthemtrade.png'
transition: slide-up
---

---
layout: 3-images
imageLeft: '/2025/images/games/unbeatable.png'
imageTopRight: '/2025/images/games/poe.png'
imageBottomRight: '/2025/images/games/diablo.png'
transition: slide-up
---

---
layout: 3-images
imageLeft: '/2025/images/games/mariokart_1.jpg'
imageTopRight: '/2025/images/games/mh_1.png'
imageBottomRight: '/2025/images/games/mh_2.png'
transition: slide-up
---

---
layout: 3-images
imageLeft: '/2025/images/games/split-fiction.png'
imageTopRight: '/2025/images/games/zzz_2.png'
imageBottomRight: '/2025/images/games/zzz_1.png'
transition: slide-up
---

---
layout: 3-images
imageLeft: '/2025/images/games/satisfactory_1.png'
imageTopRight: '/2025/images/games/satisfactory_2.png'
imageBottomRight: '/2025/images/games/satisfactory_3.png'
transition: slide-up
---

---
layout: 3-images
imageLeft: '/2025/images/games/mtg_5.png'
imageTopRight: '/2025/images/games/mtg_2.png'
imageBottomRight: '/2025/images/games/mtg_4.png'
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




```mermaid
graph LR
    Discord["Discord"]
    Electron["Electron"]
    Chromium["Chromium"]
    Node["Node.js"]
    V8["V8"]
    libuv["libuv"]
    SSL["OpenSSL"]
    Skia["Skia"]
    Freetype["Freetype"]
    ICU["ICU"]
    CPP["C++"]
    LLVM["LLVM"]
    Glibc["glibc"]
    Linux["Linux"]
    Discord --> Electron
    Discord --> Node
    Electron --> Chromium
    Electron --> V8
    Node --> V8
    Node --> libuv
    Node --> SSL
    Chromium --> Skia
    Chromium --> V8
    Skia --> Freetype
    Chromium --> ICU
    Freetype --> CPP
    ICU --> CPP
    libuv --> CPP
    SSL --> CPP
    CPP --> LLVM
    CPP --> Glibc
    LLVM --> Linux
    Glibc --> Linux
```

We need to define all of these with the build instructions, and their dependencies too!

---
layout: center
transition: slide-up
---

# Building everything from source is slow

What if we had a **shared cache** of pre-built packages based on these instructions. Instead of building everything from source every time, we could just download the packages from the cache!

---
layout: center
transition: slide-up
---

# Nix is a Language and a Package Manager that does both of these things

Also known as the Nix DSL (Domain Specific Language) and nixpkgs (The Nix package manager/registry).

It originated in 2003 as a research project by Eelco Dolstra at Utrecht University.

His 2006 doctoral thesis, **The Purely Functional Software Deployment Model**, describes a declarative and functional approach to software deployment and lays out the design of the Nix package manager.

---
layout: intro-image-right
image: '/2025/images/map_repo_size_fresh.svg'
transition: slide-up
---

# It's also the [largest and most up to date collection of packages](https://repology.org/repositories/graphs)

We currently have build instructions for over 120,000 packages, and a public, shared cache for all of them!

---
layout: center
transition: slide-up
---

# What do we use it for?

First, install nix on linux, mac, windows, and more ([download](https://nixos.org/download/))

---
layout: two-cols-header
transition: slide-up
---

# Run packages without installing them


::left::

```sh
nix-shell -p nodejs_22
```

::right::
<img src="/2025/images/nix-node.png" alt="nix nodejs" />

---
layout: two-cols-header
transition: slide-up
---

# Open development environments

::left::

```nix

{
  devShells.default = pkgs.mkShell {
    buildInputs = with pkgs; [
      nodejs_22
      pnpm
    ];
    shellHook = ''
      node --version
      pnpm --version
      pnpm i
      pnpm dev
    '';
  };
}
```

::right::

<img src="/2025/images/nix-devshell.png" alt="nix devshell" />

---
layout: center
transition: slide-up
---

# Or: Nix + Home Manager

Use nix to configure your entire user environment declaratively.

---
layout: center
transition: slide-up
---

# Installing general applications

```nix
 home-manager.users.${username} =
  {
    # Define general applications to be installed without further configuration
    packages = with pkgs; [
      bitwarden-desktop
      discord
      signal-desktop
      element-desktop
      tidal-hifi
    ];
  }
```

---
layout: center
transition: slide-up
---

# Configuring fully supported programs, e.g. firefox

```nix
 home-manager.users.${username} =
  {
    programs.firefox = {
      # This is all we need to do to install firefox
      enable = true; 

      # Install extensions
      extensions = with pkgs.nur.repos.rycee.firefox-addons; [
        ublock-origin
      ];

      # Configure search
      search.default = "ddg"; # DuckDuckGo

      # Deep integration with full set of internal firefox settings
      settings = { 
        "browser.startup.homepage" = "https://diluz.io/sebastian";
        "privacy.trackingprotection.enabled" = true;
      };    
    };
  }
```

---
layout: statement
transition: slide-up
---

## We can use this configuration on all our machines

PC, personal laptop, work laptop, servers, etc.

---
layout: statement
transition: slide-up
---

# What if we built an entire operating system around this concept?

---
layout: intro-image-right
image: '/2025/images/nixos-logo.svg'
transition: slide-up
---

# NixOS

A Linux distribution where the entire operating system is built and managed using the Nix package manager.

---
layout: center
transition: slide-up
---

# What makes NixOS special?

- Reproducibility: The entire system state can be applied to any machine, yielding the same results.
- Declarative configuration: The entire system configuration is defined using nix expressions.
- Atomic upgrades and rollbacks: System updates are atomic, meaning they either complete successfully or not at all. If an update causes issues, users can easily roll back to a previous system state.

---
layout: center
transition: slide-up
---

  # Set up foundational settings


```nix
{
  # Time zone
  time.timeZone = "Europe/Berlin";

  # Localization
  i18n.defaultLocale = "en_US.UTF-8";
  i18n.extraLocaleSettings = {
    LC_MEASUREMENT = "de_DE.UTF-8";
    LC_MONETARY = "de_DE.UTF-8";
    LC_NUMERIC = "de_DE.UTF-8";
    LC_PAPER = "de_DE.UTF-8";
    LC_TIME = "de_DE.UTF-8";
  };
}
```

---
layout: center
transition: slide-up
---

  # Set up graphics card


```nix
{
  services.xserver.videoDrivers = [ "nvidia" ];
  hardware.nvidia = {
    modesetting.enable = true;
    powerManagement.enable = false;
    powerManagement.finegrained = false;
    open = false; # Don't use the open source driver
    nvidiaSettings = true;
    package = config.boot.kernelPackages.nvidiaPackages.stable;
  };
}
```

---
layout: center
transition: slide-up
---

# Configure Yubikey for login and sudo

```nix
{
  services.udev.packages = [ pkgs.yubikey-personalization ];
  services.pcscd.enable = true;
  security.pam = {
    services = {
      login.u2fAuth = true;
      sudo.u2fAuth = true;
      # for login after lockout on KDE
      kde.u2fAuth = true;
    };
    u2f.settings = {
      cue = true; # Tell users to touch the yubikey
    };
  };
}
```

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