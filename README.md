
***

<div align="center">
   <img alt="Bliss Browser logo failed to load. Click/tap here to attempt to view it" src="/Bliss_Browser_Logo1_V1_1024pxIcon_HighCompression.png" width="256" height="256" class="center"/>
  <H1>Bliss Browser OSMode</H1>
  <p>🌳️🌐️💻️ The OS mode for Bliss Browser lets you turn your computer into a netbook for as much time as you choose. A privacy-focused alternative to ChromeOS/ChromiumOS</p>
</div>

***

## Intro

OS Mode for Bliss Browser is a framework for the browser that turns the interface into a graphical shell similar to FirefoxOS, ChromeOS, and other netbook operating systems. **The OSMode shell is not an operating system**, it runs on top of one. It is designed to make a computer into a Netbook, until the user decides to disable it (via Bliss Browser settings) and have it just be a browser application within their operating system once more.

### Netbook definition

I may be outspoken here, but I believe that Netbook is still the relevant term for a computer that only runs a web browser.

### Similar projects

> **Note** This list is in A-Z order. Also, these projects are listed because they have similar aspects to Bliss Browser OSMode, but are mostly completely different in design.

- ChromeOS/ChromiumOS - A netbook operating system that is mainly a web browser operating system, although with a very bad privacy record
- FirefoxOS - A discontinued privacy friendly netbook operating system that was replaced by Google ChromeOS/Google ChromiumOS
- Windows 1.x, 2.x, 3.x, and 3.1x (Windows 1.0 - Windows 3.11) - a graphical shell that ran on top of MS-DOS
- Windows 9x (Windows 95, 98, ME) - a graphical shell that ran on top of MS-DOS

***

## Challenges

### Mobile variants

On 2023, Tuesday, February 7th, I began to deal with a new problem in the design of the browser: I have designed it for desktops, and I never considered making a mobile variant. I am trying to figure out how the browser will have to be changed to get it to run on mobile operating systems. It is also an interesting idea to have a netPDA/netPhone, opposed to a NetBook.

### iOS/iPadOS engine problem

Due to Apple Incs rule on using third party engines in iOS/iPadOS, the iOS/iPadOS versions of the browser will be severely limited, as the project will be forced to use WebKit for these variants, opposed to other engines. Maybe a rooted variant can support other engines?

***

## OS ports

OSMode repositories aren't just for turning the browser into a net operating system, they also contain fine-tuned tools and libraries required to port the browser to different operating systems. The tuned tools will work alongside the Bliss Browser core. The core will interpret the changes for each operating system and its port.

***

## Questions and answers

**Q:** Will Bliss Browser ever support ChromeOS/ChromiumOS?

**A:** No, there is no point. If a user wants a netbook operating system other than ChromeOS, they can switch over. It isn't feasible to port the browser to this platform for many reasons.

**List is incomplete**

***

## Variants

> **Note** Links marked with the :octocat: Emoji are indicators that the links are to GitHub-based repositories.

> **Note** For developers: Keep each table row limited to 4 entries.

### Linux

Special Linux builds of Bliss Browser OSMode are available for:

| <img alt="Debian logo failed to load. Click/tap here to attempt to view it" src="/Graphics/Linux/D/Debian/SVG/Debian_Logo.svg" width="256" height="256" class="center"/> | <img alt="Fedora logo failed to load. Click/tap here to attempt to view it" src="/Graphics/Linux/F/Fedora/SVG/Fedora_logo.svg" width="256" height="256" class="center"/> | <img alt="RedHat logo failed to load. Click/tap here to attempt to view it" src="/Graphics/Linux/R/RedHat/SVG/Red_Fedora.svg" width="256" height="256" class="center"/> | <img alt="Ubuntu logo failed to load. Click/tap here to attempt to view it" src="/Graphics/Linux/U/Ubuntu/PNG/Ubuntu-Legacy-logo.png" width="256" height="256" class="center"/> |
|---|---|---|---|
| [:octocat: Bliss Browser OSMode for Debian](https://github.com/seanpm2001/Bliss_Browser_OSMode_Debian-Shell/) | [:octocat: Bliss Browser OSMode for Fedora](https://github.com/seanpm2001/Bliss_Browser_OSMode_Fedora-Shell/) | [:octocat: Bliss Browser OSMode for Red Hat](https://github.com/seanpm2001/Bliss_Browser_OSMode_RedHat-Shell/) | [:octocat: Bliss Browser OSMode for Ubuntu](https://github.com/seanpm2001/Bliss_Browser_OSMode_Ubuntu-Shell/) |

| <img alt="Arch Linux logo failed to load. Click/tap here to attempt to view it" src="/Graphics/Linux/A/Arch-Linux/PNG/Arch-linux-logo.png" width="256" height="256" class="center"/> | <img alt="Gentoo logo failed to load. Click/tap here to attempt to view it" src="/Graphics/Linux/G/Gentoo-Linux/PNG/gentoo-3d-Logo.png" width="256" height="256" class="center"/> | <img alt="Linux From Scratch logo failed to load. Click/tap here to attempt to view it" src="/Graphics/Linux/L/Linux-From-Scratch/PNG/Linux-From-Scratch_LQ_Logo.png" width="256" height="256" class="center"/> | <img alt="Meadows proto-logo failed to load. Click/tap here to attempt to view it" src="/Graphics/Linux/M/Meadows/JPEG/Meadows_LowRes_PlaceholderLogo.jpeg" width="256" height="256" class="center"/> |
|---|---|---|---|
| [:octocat: Bliss Browser OSMode for Arch Linux](https://github.com/seanpm2001/Bliss_Browser_OSMode-Arch-Shell/) | [:octocat: Bliss Browser OSMode for Gentoo Linux](https://github.com/seanpm2001/Bliss_Browser_OSMode_Gentoo-Shell/) | [:octocat: Bliss Browser OSMode for Linux From Scratch (LFS)](https://github.com/seanpm2001/Bliss_Browser_OSMode-LFS-Shell/) | [:octocat: Bliss Browser OSMode for Meadows](https://github.com/seanpm2001/Bliss_Browser_OSMode-Meadows-Shell/) |

| <img alt="RPi logo failed to load. Click/tap here to attempt to view it" src="/Graphics/Linux/R/Raspberry-Pi-OS/PNG/RPI_Logo_400px.png" width="256" height="256" class="center"/> | <img alt="NixOS logo failed to load. Click/tap here to attempt to view it" src="/Graphics/Linux/N/NixOS/PNG/NixOS_Logo1.png" width="256" height="256" class="center"/> | <img alt="WacOS logo failed to load. Click/tap here to attempt to view it" src="/Graphics/Linux/W/WacOS/PNG/MacOSIcon.png" width="256" height="256" class="center"/> | <img alt="Android logo failed to load. Click/tap here to attempt to view it" src="/Graphics/Linux/A/Android/SVG/Android_logo_2019_(stacked).svg" width="256" height="256" class="center"/> |
|---|---|---|---|
| [:octocat: Bliss Browser OSMode for Raspberry Pi OS](https://github.com/seanpm2001/Bliss_Browser_OSMode_Raspberry-Pi-OS-Shell/) | [:octocat: Bliss Browser for NixOS](https://github.com/seanpm2001/Bliss_Browser_OSMode_NixOS_Shell/) | [:octocat: Bliss Browser for WacOS](https://github.com/seanpm2001/Bliss_Browser_OSMode_WacOS_Shell/) | [:octocat: Bliss Browser for Android](https://github.com/seanpm2001/Bliss_Browser_OSMode_Android_Shell/) |

| <img alt="FireOS logo failed to load. Click/tap here to attempt to view it" src="/Graphics/Linux/F/FireOS/PNG/Amazon-Fire-Logo.png" width="256" height="256" class="center"/> | <img alt="Bliss Browser logo failed to load. Click/tap here to attempt to view it" src="/Bliss_Browser_Logo1_V1_1024pxIcon_HighCompression.png" width="256" height="256" class="center"/> | <img alt="Bliss Browser logo failed to load. Click/tap here to attempt to view it" src="/Bliss_Browser_Logo1_V1_1024pxIcon_HighCompression.png" width="256" height="256" class="center"/> | <img alt="Bliss Browser logo failed to load. Click/tap here to attempt to view it" src="/Bliss_Browser_Logo1_V1_1024pxIcon_HighCompression.png" width="256" height="256" class="center"/> |
|---|---|---|---|
| [:octocat: Bliss Browser for FireOS](https://github.com/seanpm2001/Bliss_Browser_OSMode_FireOS_Shell/) | Coming soon | Coming soon | Coming soon |

> **Note** Add to list: Kubuntu, Lubuntu, Xubuntu, ~~Gentoo~~, Manjaro, ~~Arch,~~ Alpine, Puppy, ~~Raspberry Pi OS~~, RaspbianOS, OpenSUSE, ElementaryOS, etc.

### *Nix

Special builds for other UNIX-like operating systems with Bliss Browser OSMode are available for:

| <img alt="POSIX logo failed to load. Click/tap here to attempt to view it" src="/Graphics/-Nix/P/POSIX/JPEG/POSIX-3799444896.jpeg" width="256" height="256" class="center"/> | <img alt="DragonFly BSD logo failed to load. Click/tap here to attempt to view it" src="/Graphics/BSD/DragonFly/PNG/105_dragonfly-bsd-icon.png" width="256" height="256" class="center"/> | <img alt="MacOS logo failed to load. Click/tap here to attempt to view it" src="/Graphics/-Nix/M/MacOS/PNG/MacOS_Logo1.png" width="256" height="256" class="center"/> | <img alt="iOS logo failed to load. Click/tap here to attempt to view it" src="/Graphics/-Nix/I/iOS/PNG/iOS_Logo2.png" width="256" height="256" class="center"/> |
|---|---|---|---|
| [:octocat: POSIX variant of Bliss Browser OSMode](https://github.com/seanpm2001/Bliss_Browser_OSMode_POSIX-Shell/) | [DragonFly BSD](https://github.com/seanpm2001/Bliss_Browser_OSMode-DragonflyBSD-Shell/) | [:octocat: Bliss Browser for MacOS (10.10 and up)](https://github.com/seanpm2001/Bliss_Browser_OSMode_MacOS_Shell/) | [:octocat: Bliss Browser for iOS](https://github.com/seanpm2001/Bliss_Browser_OSMode_iOS_Shell/) |

| <img alt="iPadOS low quality logo failed to load. Click/tap here to attempt to view it" src="/Graphics/-Nix/I/iPadOS/PNG/iPadOS_Logo_LQ.png" width="256" height="256" class="center"/> | <img alt="Bliss Browser logo failed to load. Click/tap here to attempt to view it" src="/Bliss_Browser_Logo1_V1_1024pxIcon_HighCompression.png" width="256" height="256" class="center"/> | <img alt="Bliss Browser logo failed to load. Click/tap here to attempt to view it" src="/Bliss_Browser_Logo1_V1_1024pxIcon_HighCompression.png" width="256" height="256" class="center"/> | <img alt="Bliss Browser logo failed to load. Click/tap here to attempt to view it" src="/Bliss_Browser_Logo1_V1_1024pxIcon_HighCompression.png" width="256" height="256" class="center"/> |
|---|---|---|---|
| [:octocat: Bliss Browser for iPadOS](https://github.com/seanpm2001/Bliss_Browser_OSMode_iPadOS_Shell/) | Coming soon | Coming soon | Coming soon |

> **Note** Add to list: ~~MacOS 10.10 and newer~~, FreeBSD, OpenBSD, NetBSD, etc.

### Other

Special builds for other operating systems with Bliss Browser OSMode are available for:

| <img alt="Windows NT logo failed to load. Click/tap here to attempt to view it" src="/Graphics/Other/Windows-NT/PNG/Windows_NT_5.1_Logo_XP.png" width="256" height="256" class="center"/> | <img alt="Windows 10 logo failed to load. Click/tap here to attempt to view it" src="/Graphics/Other/Windows-10/PNG/Windows-10-logo_Square.png" width="256" height="256" class="center"/> | <img alt="Windows 11 logo failed to load. Click/tap here to attempt to view it" src="/Graphics/Other/Windows-11/JPEG/Windows-11-Logo_Square.jpeg" width="256" height="256" class="center"/> | <img alt="Bliss Browser logo failed to load. Click/tap here to attempt to view it" src="/Bliss_Browser_Logo1_V1_1024pxIcon_HighCompression.png" width="256" height="256" class="center"/> |
|---|---|---|---|
| [:octocat: Bliss Browser for Windows NT (Windows Vista and newer)](https://github.com/seanpm2001/Bliss_Browser_OSMode-Windows-NT-Shell/) | [:octocat: Bliss Browser for Windows 10](https://github.com/seanpm2001/Bliss_Browser_OSMode_Windows-10_Shell/) | [:octocat: Bliss Browser for Windows 11](https://github.com/seanpm2001/Bliss_Browser_OSMode_Windows-11_Shell/) | Coming soon |

> **Note** Add to list: ~~Windows XP, Windows 10, Windows 11 and newer~~ ReactOS, etc.

***

### File info

<details open><summary><p lang="en"><b><u>Click/tap here to expand/collapse this section</u></b></p></summary>

**File type:** `Markdown (*.md *.mkd *.mdown *.markdown)`

**File version:** `7 (2023, Thursday, February 9th at 1:50 pm PST)`

**Line count (including blank lines and compiler line):** `281`

**Current article language:** `English (EN_USA)` / `Markdown (CommonMark)` / `HTML5 (HyperText Markup Language 5.3)`

**Encoding:** `UTF-8 (Emoji 12.0 or higher recommended)`

**All times are UTC-7 (PDT/Pacific Time)** `(Please also account for DST (Daylight Savings Time) for older/newer entries up until it is abolished/no longer followed)`

> **Note** _On 2022, Sunday, March 13th at 2:00 am PST, the time jumped ahead 1 hour to 3:00 am._

> **Note** **You may need special rendering support for the `<details>` HTML tag being used in this document**

***

<details><summary><p><b>Click/tap here to expand/collapse the file history for this file</b></p></summary>

<details><summary><p><b>Version 1 (2023, Friday, January 27th at 4:25 pm PST)</b></p></summary>

- This release was made by: [:octocat: `@seanpm2001`](https://github.com/seanpm2001/)

> Changes

- [x] Started the file
- [x] Added the title section
- - [x] Added the browser logo
- - [x] Added a centered description
- [x] Added the `Intro` section
- - [x] Added the `NetBook definition` subsection
- - [x] Added the `Similar projects` subsection
- - [x] Added the `Variants` section
- - - [x] Added the `Linux` subsection
- - - [x] Added the `*Nix` subsection
- - - [x] Added the `Other` subsection
- [x] Added the file version stamp
- [ ] No other changes in version 1

</details>

<details><summary><p><b>Version 2 (2023, Thursday, February 2nd at 11:05 pm PST)</b></p></summary>

- [x] ...
- - [x] Updated the `Variants` section
- - - [x] Updated the `Linux` subsection
- - - [x] Updated the `*Nix` subsection
- - - [x] Updated the `Other` subsection
- [x] Updated the file version stamp
- [ ] No other changes in version 2

</details>

<details><summary><p><b>Version 3 (2023, Monday, February 6th at 4:27 pm PST)</b></p></summary>

- This release was made by: [:octocat: `@seanpm2001`](https://github.com/seanpm2001/)

> Changes

- [x] Updated the `Variants` section
- - [x] Updated the `*Nix` subsection, adding in MacOS
- [x] Removed the file version stamp in place of a file info section
- [x] Added the `file info` section
- - [x] Added the version number
- - [x] Added the version date
- - [x] Added the line count
- [x] Added the `file history` section
- - [x] Added an entry for version 1
- - [x] Added an entry for version 2
- - [x] Added an entry for version 3
- [x] Added the footer 
- [ ] No other changes in version 3

</details>

<details><summary><p><b>Version 4 (2023, Monday, February 6th at 4:30 pm PST)</b></p></summary>

- This release was made by: [:octocat: `@seanpm2001`](https://github.com/seanpm2001/)

> Changes

- [x] Minor fix: added a missing `</details>` tag to the `file history` section
- [x] Updated the `file info` section
- - [x] Updated the version number
- - [x] Updated the version date
- - [x] Updated the line count
- [x] Updated the `file history` section
- - [x] Added an entry for version 4
- [ ] No other changes in version 4

</details>

<details><summary><p><b>Version 5 (2023, Tuesday, February 7th at 6:06 pm PST)</b></p></summary>

- This release was made by: [:octocat: `@seanpm2001`](https://github.com/seanpm2001/)

> Changes

- ...
- - [x] Updated the `*Nix` subsection, adding in iOS and iPadOS
- [x] Added the `Challenges` section
- - [x] Added the `Mobile variants` subsection
- - [x] Added the `iOS/iPadOS engine problem` subsection
- [x] Added the `OSPorts` section
- [x] Updated the `file info` section
- - [x] Updated the version number
- - [x] Updated the version date
- - [x] Updated the line count
- [x] Updated the `file history` section
- - [x] Added an entry for version 5
- [ ] No other changes in version 5

</details>

<details><summary><p><b>Version 6 (2023, Wednesday, February 8th at 3:36 pm PST)</b></p></summary>

- This release was made by: [:octocat: `@seanpm2001`](https://github.com/seanpm2001/)

> Changes

- ...
- - [x] Updated the `Linux` subsection, adding in NixOS and WacOS
- [x] Updated the `file info` section
- - [x] Updated the version number
- - [x] Updated the version date
- - [x] Updated the line count
- [x] Updated the `file history` section
- - [x] Added an entry for version 6
- [ ] No other changes in version 6

</details>

<details><summary><p><b>Version 7 (2023, Thursday, February 9th at 1:50 pm PST)</b></p></summary>

- This release was made by: [:octocat: `@seanpm2001`](https://github.com/seanpm2001/)

> Changes

- [x] Added the `Questions and answers` section
- ...
- - [x] Updated the `Linux` subsection, adding in Android and FireOS
- - [x] Updated the `OtherOS` subsection, adding in Windows 10 and Windows 11
- [x] Updated the `file info` section
- - [x] Updated the version number
- - [x] Updated the version date
- - [x] Updated the line count
- [x] Updated the `file history` section
- - [x] Added an entry for version 7
- [ ] No other changes in version 7

</details>

</details>

***

<!-- TEMPLATE

| <img alt="Bliss Browser logo failed to load. Click/tap here to attempt to view it" src="/Bliss_Browser_Logo1_V1_1024pxIcon_HighCompression.png" width="256" height="256" class="center"/> | <img alt="Bliss Browser logo failed to load. Click/tap here to attempt to view it" src="/Bliss_Browser_Logo1_V1_1024pxIcon_HighCompression.png" width="256" height="256" class="center"/> | <img alt="Bliss Browser logo failed to load. Click/tap here to attempt to view it" src="/Bliss_Browser_Logo1_V1_1024pxIcon_HighCompression.png" width="256" height="256" class="center"/> | <img alt="Bliss Browser logo failed to load. Click/tap here to attempt to view it" src="/Bliss_Browser_Logo1_V1_1024pxIcon_HighCompression.png" width="256" height="256" class="center"/> |
|---|---|---|---|
| Coming soon | Coming soon | Coming soon | Coming soon |

!-->
