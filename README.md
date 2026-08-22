# RadMageIRL

I have been programming since 1993. I only started publishing publicly in 2026.

That gap is not modesty. Code was something I wrote to solve the problem in front
of me, and once the problem was solved there was no particular reason to show
anyone. Thirty-three years of that adds up to a lot of tools nobody ever saw. I
am fixing that now.

## Where this started

x86 assembly, then C, then C++, on hardware that punished you for guessing. About
twenty-five years professionally since then, in systems, networking and
infrastructure: Windows and Linux, enterprise environments, virtualization, and
the parts of a network that only ever get looked at once they have broken.

## One thing, ten thousand times

I have never been especially interested in collecting technologies. I am
interested in systems, and the useful property of systems is that the reasoning
transfers.

Networking taught me to think in protocols: state, negotiation, and what happens
when a message simply does not arrive. Programming taught me abstraction, and how
to build one that holds under weight. Systems administration taught me failure
modes, which is a polite way of saying it taught me what actually breaks rather
than what the documentation predicts will break. Reverse engineering taught me
not to trust the abstraction, because underneath every clean interface is
something that does not behave the way the interface claims.

Those four models travel. A hostile file format and a misbehaving switch are the
same problem wearing different clothes.

## What is here

Everything in this account exists because I wanted it to exist. None of it was
built to be a portfolio piece, which is why some of it is a polished
cross-platform application and some of it is a 512-byte offset fix for a SNES
fan translation.

**[re-moct](https://github.com/RadMageIRL/re-moct)** - I missed MOC. So I rebuilt
the idea for Linux and Windows, and then kept going. C++20 on PDCursesMod/ncurses, with
CD ripping, AccurateRip verification and internet radio.

**[LinuxUtils](https://github.com/RadMageIRL/LinuxUtils)** - I had accumulated
enough admin tools that they needed somewhere to live. Standard library only,
read-only by default, and each one says plainly when it cannot determine
something rather than guessing.

**[DQVSNES4PARTYPATCH](https://github.com/RadMageIRL/DQVSNES4PARTYPATCH)** - The
existing patch was broken. It turned out to be a 512-byte alignment issue. I
fixed it.

**[DQVI_NOPRGRESS_MENU_FIX](https://github.com/RadMageIRL/DQVI_NOPRGRESS_MENU_FIX)** -
Three hard hangs in a different SNES fan translation. One was three deleted
bytes. One was a text buffer parked in memory the original game wipes,
which took gigabytes of instruction traces to find and is fixed by moving it. The
third was original Enix code. The Gold display was not visible in the NoPrgress patch,
added it back in the English translation.

**[renorm](https://github.com/RadMageIRL/renorm)** - I needed a filename renamer
I could trust across thousands of files at once. Plan first, execute second, undo
if it was wrong.

**[Codex-Notes-HTML](https://github.com/RadMageIRL/Codex-Notes-HTML)** - Every
note app annoyed me in a slightly different way. This one is a single HTML file.

**[SecurePasswordGenerator](https://github.com/RadMageIRL/SecurePasswordGenerator)** -
Every password generator on the web asks you to trust a stranger's server with
the output. This one never leaves your browser. AWESOME MODE is just for fun.

## Now

Publishing the backlog, and building the next thing. If any of it turns out to be
useful to you, that is a pleasant side effect rather than the plan.

Red Mage, FFXI, since launch

<img width="728" height="90" alt="remoct-banner-728x90" src="https://github.com/user-attachments/assets/4ef8e3fb-ee03-47e5-b5b7-4a35360be04f" />
<br><br>
<img width="728" height="90" alt="whittle-banner-728x90-2" src="https://github.com/user-attachments/assets/c940965d-4e58-4766-a686-1355586778cd" />

