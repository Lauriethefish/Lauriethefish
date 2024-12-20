**Hi, I'm a developer working on several open-source projects you might be interested in :)**

Do check out a few highlights below.

If you're particularly enamoured of a project, then consider [sponsoring me](https://github.com/sponsors/Lauriethefish).
It really means a lot - it helps me justify spending time maintaining projects.

## Stuff I maintain at the moment
### ModsBeforeFriday

[ModsBeforeFriday](https://github.com/Lauriethefish/ModsBeforeFriday) (or MBF, to be extra confusing) is a modding tool for Beat Saber on
Meta Quest headsets. Its aim is to streamline the process of mod installation, such that you can get your modded game up and running in only a couple
of clicks! 

MBF automatically downgrades the game, installs the modloader and all the core mods that you need to get started. It runs entirely within a web browser,
so you don't even need to install anything on your PC.
It's written with a Rust backend, and TypeScript + React frontend, and accesses your Quest via WebUSB.

### QuestPatcher

In the early days of Gorilla Tag modding, I make a small tool for modding il2cpp applications on the Oculus Quest and Oculus Quest 2. This is [QuestPatcher](https://github.com/Lauriethefish/QuestPatcher). It has now reached over 900,000 downloads. 

The QMOD format used in QuestPatcher was later adopted by [BMBF](https://bmbf.dev/) (which is now defunct) and MBF, seen above.
QMOD files can be easily manipulated using the [QuestPatcher.QMod](https://github.com/Lauriethefish/QuestPatcher.QMod) NuGet package.

QuestPatcher is now mostly used by Beat Saber mod developers who need a convenient desktop interface for mod installation.

### NandroidFS

[NandroidFS](https://github.com/Lauriethefish/nandroidfs) is a filesystem for Windows which allows Android devices connected to your PC via the Android Debug Bridge to be mounted as though they were a regular drive connected to your PC. (with a drive letter for each device)
This is in contrast to the Windows Explorer MTP integration, which is slow and clunky, and doesn't allow other applications to treat the Android device
as a regular drive (it's just for GUI file management).

NandroidFS is not a kernel mode driver, but instead uses Dokan to allow filesystem-in-user-space.

## Other cool things I've made

### OCR ERL Interpreter

OCR Exam Reference Language (ERL) is a pseudocode language used for the OCR GCSE exam in Computer Science. Despite being "pseudocode", the language
is fairly formally defined, so it is possible to write an interpreter that can run ERL code.

My [ERL interpreter](https://github.com/Lauriethefish/ocr-erl) isn't quite fully featured, but focuses on performance, using a stack-based VM
to achieve very efficient execution.

### Factorio Computer

A bit random, but a while back I made a computer in the video game Factorio, alongside a compiler that can be used to write programs
for the computer in a high level language called LFL. (Laurie's Factorio language).

[Here](https://github.com/Lauriethefish/FactorioComputer) it is, if you're interested.