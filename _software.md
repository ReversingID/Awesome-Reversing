# Awesome Software Reverse Engineering

A curated list of awesome reverse engineering resources to make you better! 

Managed by Reversing.ID for the reversing community.

## Introduction 

`Software Reverse Engineering` focus on code, related data, and architecture which build a complete software.

The goals:

- Recover lost information, or to make documentation.
- Detect side effects (bugs, backdoor, vulnerabilities)
- Synthesis higher abstraction.
- Facilitate reuse.

In most case, the target of Software Reversing is code in compiled form (native or intermediate), either executable or libraries.

## Table of Contents

- Resources
    - [Books](#books)
    - [White Papers](#hite-papers)
    - [Articles](#articles)
    - [Courses](#courses)
    - [Channels](#channels)
    - [Practices](#practices)
    - [References](#references)
- Tools
    - [Hex Editors](#hex-editors)
    - [Binary Format](#binary-format)
    - [Bytecode Editor](#bytecode-editors)
    - [Disassemblers & Decompilers](#disassemblers--decompilers)
    - [Debuggers](#debuggers)
    - [Behavior Analysis](#behavior-analysis)
    - [Dynamic Binary Instrumentation](#dynamic-binary-instrumentation)
    - [Binary Analysis Framework](#binary-analysis-framework)
    - [Code Emulators](#code-emulators)
    - [Injectors](#injectors)
    - [HTTP Intercept Proxy](#http-intercept-proxy)
    - [Reconstructors](#reconstructors)
    - [Unpackers](#unpackers)
    - [Obfuscators](#obfuscators)
    - [Deobfuscators](#deobfuscators)
    - [Binary Visualization](#binary-visualization)
    - [Document Analysis](#document-analysis)
    - [Misc](#misc)
- Scripting
    - [IDA Pro](#ida-script)
    - [Ghidra](#ghidra-script)

- - - 

## Books

Reversing Concept

* [Reverse Engineering for Beginners](http://beginners.re/)
* [Practical Reverse Engineering](http://amzn.com/B00IA22R2Y)
* [Reversing: Secrets of Reverse Engineering](http://amzn.com/B007032XZK)
* [Practical Malware Analysis](http://amzn.com/1593272901)

Tools

* [The IDA Pro Book](http://amzn.com/1593272898)

Assembly and languages

* [Assembly Language for Intel-Based Computers (5th Edition) ](http://a.co/4OR6I9U)

Specific topic on Software Reverse Engineering

* [Windows Internals Part 1](http://amzn.com/0735648735) [Part 2](http://amzn.com/0735665877)
* [Inside Windows Debugging](http://amzn.com/0735662789)
* [iOS Reverse Engineering](https://github.com/iosre/iOSAppReverseEngineering)

## White Papers

* [Next Generation debugger for reverse engineering](https://www.blackhat.com/presentations/bh-europe-07/ERSI/Whitepaper/bh-eu-07-ersi-WP-apr19.pdf)
* [Behind Enemy Lines Reverse Engineering C++ in Modern Ages](https://corecppil.github.io/CoreCpp2019/Presentations/Gal_Behind_Enemy_Lines_Reverse_Engineering_Cpp_in_Modern_Ages.pdf)
* [Overcoming Java Vulnerabilities](https://www2.gemalto.com/download/OvercomingJavaVulnerabilities_WP_(A4)_web.pdf)
* [Reverse engineering tools review](https://www.pelock.com/articles/reverse-engineering-tools-review)

## Articles

* [Intercepting DLL libraries calls. API hooking in practice](https://www.pelock.com/articles/intercepting-dll-libraries-calls-api-hooking-in-practice)
* [Windows Hot Patching Mechanism Explained](https://dev.to/pelock/windows-hot-patching-mechanism-explained-2m1f)
* [How to write a CrackMe for a CTF competition](https://www.pelock.com/articles/how-to-write-a-crackme-for-a-ctf-competition)
* [Anti reverse engineering. Malware vs Antivirus Software](https://www.pelock.com/articles/reverse-engineering-tools-review)
* [Code of destruction – malware analysis](https://www.pelock.com/articles/code-of-destruction-malware-analysis)
* [Polymorphic Encryption Algorithms](https://www.pelock.com/articles/polymorphic-encryption-algorithms)
* [Reversing reading]() - coming soon.

## Courses

*Reverse Engineering Courses*

* [Lenas Reversing for Newbies](https://tuts4you.com/download.php?list.17)
* [Open Security Training](http://opensecuritytraining.info/Training.html)
* [Dr. Fu's Malware Analysis](http://fumalwareanalysis.blogspot.sg/p/malware-analysis-tutorials-reverse.html)
* [Binary Auditing Course](http://www.binary-auditing.com/)
* [TiGa's Video Tutorials](http://www.woodmann.com/TiGa/)
* [Legend of Random](https://tuts4you.com/download.php?list.97)
* [Practical Malware Analysis](https://samsclass.info/126/126_S17.shtml)
* [Modern Binary Exploitation](http://security.cs.rpi.edu/courses/binexp-spring2015/)
* [RPISEC Malware Course](https://github.com/RPISEC/Malware)
* [begin.re](https://www.begin.re/)
* [RE101](https://securedorg.github.io/RE101/)
* [RE102](https://securedorg.github.io/RE102/)
* [ARM Assembly Basics](https://azeria-labs.com/writing-arm-assembly-part-1/)
* [Offensive and Defensive Android Reversing](https://github.com/rednaga/training/raw/master/DEFCON23/O%26D%20-%20Android%20Reverse%20Engineering.pdf)

## Channels

*Binary Analysis Channels*

* [OALabs](https://www.youtube.com/channel/UC--DwaiMV-jtO-6EvmKOnqg)
* [MalwareTech](https://www.youtube.com/channel/UCLDnEn-TxejaDB8qm2AUhHQ)
* [GynvaelEN](https://www.youtube.com/user/GynvaelEN)
* [VirusBtn](https://www.youtube.com/user/virusbtn)
* [Intro to WinDBG](https://www.youtube.com/playlist?list=PLhx7-txsG6t6n_E2LgDGqgvJtCHPL7UFu)
* [hasherzade](https://www.youtube.com/channel/UCNWVswPNgn5kutPNa5sprkg)
* [Colin Hardy](https://www.youtube.com/channel/UCND1KVdVt8A580SjdaS4cZg)
* [MalwareAnalysisHedgehog](https://www.youtube.com/channel/UCVFXrUwuWxNlm6UNZtBLJ-A)
* [LiveOverflow](https://www.youtube.com/watch?v=iyAyN3GFM7A&list=PLhixgUqwRTjxglIswKp9mpkfPNfHkzyeN)

## Practices

*Practice Reverse Engineering*

* [Reversing.ID Crackmes Repository](https://github.com/ReversingID/Crackmes-Repository/)
* [Crackmes.one](http://www.crackmes.one/)
* [OSX Crackmes](https://reverse.put.as/crackmes/)
* [ESET Challenges](http://www.joineset.com/jobs-analyst.html)
* [Flare-on Challenges](http://flare-on.com/)
* [Github CTF Archives](http://github.com/ctfs/)
* [Reverse Engineering Challenges](http://challenges.re/)
* [xorpd Advanced Assembly Exercises](http://www.xorpd.net/pages/xchg_rax/snip_00.html)
* [Virusshare.com](http://virusshare.com/)
* [Contagio](http://contagiodump.blogspot.com/)
* [Malware-Traffic-Analysis](https://malware-traffic-analysis.com/)
* [Malshare](http://malshare.com/)
* [Malware Blacklist](http://www.malwareblacklist.com/showMDL.php)
* [malwr.com](https://malwr.com/)
* [vxvault](http://vxvault.net/)

## References

Learning Assembly

* [Low-level Code Reference](https://github.com/ReversingID/LowLevelCode-Reference)
* [Assembly code size optimization tricks](https://dev.to/pelock/assembly-code-size-optimization-tricks-2abd)
* [When and how to use an assembler. Assembly programming basics](https://www.pelock.com/articles/when-and-how-to-use-an-assembler-assembly-programming-basics)

Intermediate Representation

* [LLVM IR](https://llvm.org/docs/LangRef.html)
* [REIL](https://www.zynamics.com/binnavi/manual/html/reil_language.htm)
* [OpenREIL](https://github.com/Cr4sh/openreil)

- - - 

## Hex Editors

Hex editor lets you view/edit the binary data of a file.

Multi/cross platform

* [010 Editor](http://www.sweetscape.com/010editor/)
* [wxHexEditor](https://www.wxhexeditor.org/)

Windows 

* [HxD](https://mh-nexus.de/en/hxd/)
* [Hex Workshop](http://www.hexworkshop.com/)
* [Hexinator](https://hexinator.com/)
* [HIEW](http://www.hiew.ru/)

Mac OS X

* [HexFiend](http://ridiculousfish.com/hexfiend/)

## Binary Format

File information and format identifier

* [file](https://linux.die.net/man/1/file)
* [TrID](http://mark0.net/soft-trid-e.html)
* [nm](https://linux.die.net/man/1/nm) - view symbols

Executable detector

* [Detect It Easy](http://ntinfo.biz/)
* [PEiD](https://tuts4you.com/download.php?view.398)

Executable explorer

* [CFF Explorer](http://www.ntcore.com/exsuite.php)
* [Cerbero Profiler](http://cerbero.io/profiler/)  //  [Lite PE Insider](http://cerbero.io/peinsider/)
* [PeStudio](http://www.winitor.com/)
* [PPEE](https://www.mzrst.com/)
* [PE Bear](https://hshrzd.wordpress.com/pe-bear/)
* [MachoView](https://github.com/gdbinit/MachOView)

Dependency check

* [DependencyWalker](http://www.dependencywalker.com/)
* [slid](https://github.com/arvinddoraiswamy/slid) - statically linked library detector.

Format parser and modification

* [Kaitai Struct](https://kaitai.io) - develop format parsers by declarative approach 
* [LIEF](https://lief.quarkslab.com/) - Library to Instrument Executable Formats, easily parse, modify and abstract many file formats.
* [QuickBMS](http://aluigi.altervista.org/quickbms.htm) - easily extract and modify file format with support of encryption, compressions, obfuscation, and other algorithms.

## Bytecode Editors

Java bytecode editor

* [Recaf](https://github.com/Col-E/Recaf)
* [JByteMode](https://github.com/GraxCode/JByteMod-Beta)
* [dirtyJOE](http://dirty-joe.com/)

## Disassemblers & Decompilers

Native code disassembler and decompiler

* [Ghidra](https://ghidra-sre.org/)
* [IDA Pro](https://www.hex-rays.com/products/ida/index.shtml)
* [Binary Ninja](https://binary.ninja/)
* [Relyze Desktop](https://relyze.com)
* [Radare2](http://www.radare.org/r/) // [Cutter](https://cutter.re)
* [Hopper](http://hopperapp.com/)
* [fREedom](https://github.com/cseagle/fREedom)
* [Retdec](https://retdec.com/)
* [Snowman](https://derevenets.com/)
* [objdump](http://linux.die.net/man/1/objdump)
* [Medussa](https://github.com/wisk/medusa)
* [Plasma](https://github.com/joelpx/plasma)
* [Capstone](http://www.capstone-engine.org/) - lightweight multi-platform, multi-architecture disassembly framework based on LLVM.
* [distorm3](https://github.com/gdabah/distorm) - lightweight library for disassembling binary stream.
* [zydis](https://github.com/zyantific/zydis) - fast and lightweight x86/x86-64 disassembler library.

Android application disassembler / decoder

* [JEB2](https://www.pnfsoftware.com/jeb2/) - eclipse-based integrated reverse engineering platform for analyzing various parts of Android application components.

Java decompiler

* [Bytecode Viewer](https://bytecodeviewer.com/) - aggregate of various tools
* [Procyon](https://bitbucket.org/mstrobel/procyon)
* [CFR](http://www.benf.org/other/cfr/)
* [FernFlower](https://github.com/fesh0r/fernflower)
* [Krakatau](https://github.com/Storyyeller/Krakatau)
* [Luyten](https://github.com/deathmarine/Luyten)

.NET decompiler

* [dnSpy](https://github.com/0xd4d/dnSpy)
* [JustDecompile](https://www.telerik.com/products/decompiler.aspx)
* [dotPeek](https://www.jetbrains.com/decompiler/)
* [ILSpy](http://www.ilspy.net/)

Python decompiler

* [uncompyle6](https://pypi.org/project/uncompyle6/)
* [decompile3](https://github.com/rocky/python-decompile3) - reworking and refactoring of `uncompyle6` which focus on Python 3.7+

Flash decompiler

* [JPEXS Flash Decompiler](https://github.com/jindrapetrik/jpexs-decompiler) - open source SWF decompiler and editor, convert SWF to FLA, edit ActionScript, replace resources (images, sounds, texts, fonts).
* [Flare](http://www.nowrap.de/flare.html) - Extract all scripts from SWF.

Delphi decompiler

* [Interactive Delphi Reconstructor](https://github.com/crypto2011/IDR)

Lua decompiler

* [UnLuac](https://sourceforge.net/projects/unluac/) - decompiler for Lua 5.0 - 5.4 and require debugging information (non-stripped).
* [LuaDec](https://github.com/viruscamp/luadec) - decompiler based on luadec 5.0.x and LuaDec51.

AutoIT decompiler

* [myAut2Exe](https://github.com/dzzie/myaut_contrib) - scan and extract the AutoIT script.
* [Exe2Aut](http://domoticx.com/autoit3-decompiler-exe2aut) - extract the AutoIT script by running it.

Ethereum (EVM) Solidity disassembler / decompiler

* [evmdis](https://github.com/Arachnid/evmdis) - EVM disassembler by static analysis on the bytecode.
* [pyevmasm](https://github.com/crytic/pyevmasm) - assembler and disassembler library for EVM (Ethereum Virtual Machine).

## Debuggers

Multi/cross platform

* [GDB](https://www.gnu.org/software/gdb/)
* [lldb](http://lldb.llvm.org/)
* [vdb](https://github.com/vivisect/vivisect)

Windows

* [WinDbg](https://docs.microsoft.com/en-us/windows-hardware/drivers/debugger/debugger-download-tools)
* [x64dbg](http://x64dbg.com/#start)
* [Immunity Debugger](http://debugger.immunityinc.com/)

Linux

* [QIRA](http://qira.me/) - timeless debugger which track all state while program is running.
* [EDB](http://www.codef00.com/projects#debugger)

Virtual Machine Introspection for debugging

* [rVMI](https://github.com/fireeye/rVMI)
* [r2vmi](https://github.com/Wenzel/r2vmi)

Hypervisor debugger

* [HyperDbg](https://github.com/rmusser01/hyperdbg/) - minimalistic hypervisor with hardware-assisted virtualization to debug kernel.

GDB enrichment

* [PEDA](https://github.com/longld/peda)
* [GEF](https://github.com/hugsy/gef)
* [Voltron](https://github.com/snare/voltron) - also available for LLDB, VDB, and WinDbg

OllyDbg variant

* [OllyDbg v1.10](http://www.ollydbg.de/)
* [OllyDbg v2.01](http://www.ollydbg.de/version2.html)
* [OllySnD](https://tuts4you.com/download.php?view.2061)
* [Olly Shadow](https://tuts4you.com/download.php?view.6)
* [Olly CiMs](https://tuts4you.com/download.php?view.1206)
* [Olly UST_2bg](https://tuts4you.com/download.php?view.1206)

Graphic Debugger

* [RenderDoc](https://renderdoc.org/)
* [PIX](https://blogs.msdn.microsoft.com/pix/download/)

## Behavior Analysis

Network simulation

* [iNetSim](http://www.inetsim.org/)
* [Fakenet](http://practicalmalwareanalysis.com/fakenet/)

Packet Capture

* [SmartSniff](http://www.nirsoft.net/utils/smsniff.html)
* [Wireshark](https://www.wireshark.org/download.html)

Process

* [ProcessHacker](https://processhacker.sourceforge.io/)
* [Process Explorer](https://technet.microsoft.com/en-us/sysinternals/processexplorer)
* [Autoruns](https://technet.microsoft.com/en-us/sysinternals/bb963902)

Tracer

* [API Monitor](http://www.rohitab.com/apimonitor)
* [Process Monitor](https://technet.microsoft.com/en-us/sysinternals/processmonitor)
* [SpyStudio](https://www.nektra.com/products/spystudio-api-monitor/)
* [fibratus](https://github.com/rabbitstack/fibratus) - explore and trace windows kernel
* [TCPView](https://docs.microsoft.com/en-us/sysinternals/downloads/tcpview)
* [CDA: Code Dynamic Analysis](http://split-code.com/cda.html)

Sandbox

* [Noriben](https://github.com/Rurik/Noriben)
* [Cuckoo](https://www.cuckoosandbox.org/)

Misc

* [Objective-See Utilities](https://objective-see.com/products.html)
* [XCode Instruments](https://developer.apple.com/xcode/download/) - XCode Instruments for Monitoring Files and Processes [User Guide](https://developer.apple.com/library/watchos/documentation/DeveloperTools/Conceptual/InstrumentsUserGuide/index.html)
* [dtrace script for Mac](http://dtrace.org/blogs/brendan/2011/10/10/top-10-dtrace-scripts-for-mac-os-x/) - sudo dtruss = strace [dtrace recipes](http://mfukar.github.io/2014/03/19/dtrace.html)
* [fs_usage](https://developer.apple.com/library/mac/documentation/Darwin/Reference/ManPages/man1/fs_usage.1.html) - report system calls and page faults related to filesystem activity in real-time.  File I/O: fs_usage -w -f filesystem
* [dmesg](https://developer.apple.com/library/mac/documentation/Darwin/Reference/ManPages/man8/dmesg.8.html) - display the system message buffer

## Dynamic Binary Instrumentation

Native 

* [DynamoRIO](http://www.dynamorio.org) - runtime code manipulation system that supports code transformation on any part of program.
* [Frida](https://frida.re) - scriptable DBI toolkit for cross-platform target.
* [Pin](https://software.intel.com/en-us/articles/pin-a-dynamic-binary-instrumentation-tool)
* [QBDI](https://qbdi.quarkslab.com/) - modular, cross-platform, and cross-architecture DBI framework backed by LLVM.

.NET

- [Hawkeye2](https://github.com/odalet/Hawkeye2) - view, edit, analyze, and invoke (almost) any object from .net applications.
- [UnityDoorstop](https://github.com/NeighTools/UnityDoorstop) - execute managed assemblies inside Unity as early as possible.

## Binary Analysis Framework

* [Angr](http://angr.io/) - python framework for analyzing binaries, combines both static and dynamic symbolic (concolic) analysis.
* [Triton](https://triton.quarkslab.com) - dynamic binary analysis (DBA) framework.
* [BAP](http://binaryanalysisplatform.github.io/) - suite of utilities and libraries that enable analysis of programs in their machine representations.
* [BitBlaze](http://bitblaze.cs.berkeley.edu/)
* [PANDA](https://github.com/panda-re/panda) - Platform for Architecture-Neutral Dynamic Analysis, built on QEMU system emulator, analyzecode in runtime.
* [BARF](https://github.com/programa-stic/barf-project)
* [S2E](https://s2e.systems/) - platform for in-vivo analysis of software systems.
* [miasm](https://miasm.re/) - analyze / modify / generate binary program with python.
* [soot](https://github.com/soot-oss/soot) - java optimization framework

Symbolic Execution (only)

* [KLEE](https://klee.github.io/) - dynamic symbolic execution engine built on top of the LLVM compiler infrastructure
* [manticore](https://github.com/trailofbits/manticore/) - symbolic execution tool for analysis of smart contracts and binaries.
* [Kite](http://www.cs.ubc.ca/labs/isd/Projects/Kite/) - conflict-driven symbolic execution tool (proof of concept)
* [jCUTE](https://github.com/osl/jcute) - Java Concolic Unit Testing Engine, automatically generate unit tests for Java programs.
* [ExpoSE](https://github.com/ExpoSEJS/ExpoSE) - dynamic symbolic execution engine for JavaScript.
* [ESILSolve](https:/github.com/aemmitt-ns/esilsolve) - python symbolic execution framework using r2 and ESIL.

Binary lifting

* [McSema](https://github.com/lifting-bits/mcsema) - framework for lifting x86, amd64, and aarch64 program binareis to LLVM bitcode.

Theorem prover and solver

* [Z3](https://github.com/Z3Prover/z3) - cross-platform satisfiability modulo theory 
* [STP](https://stp.github.io/)
* [CVC4](https://cvc4.github.io/)
* [Boolector](https://boolector.github.io/)

## Code Emulators

* [unicorn](https://github.com/unicorn-engine/unicorn)
* [libemu](http://libemu.carnivore.it)
* [pegasus](https://github.com/imugee/pegasus)

## Injectors

Windows

* [PolyHook](https://github.com/stevemk14ebr/PolyHook)
* [EasyHook](https://easyhook.github.io/)
* [Deviare2](https://github.com/nektra/Deviare2)
* [Xenos](https://github.com/DarthTon/Xenos)

## HTTP Intercept Proxy

* [Fiddler](https://www.telerik.com/fiddler)
* [ZAP](https://www.owasp.org/index.php/OWASP_Zed_Attack_Proxy_Project)
* [Charles](https://www.charlesproxy.com/)

## Reconstructors

Import reconstructor

* [ImpRec](http://www.woodmann.com/collaborative/tools/index.php/ImpREC)
* [Scylla](https://github.com/NtQuery/Scylla)
* [LordPE](http://www.woodmann.com/collaborative/tools/images/Bin_LordPE_2010-6-29_3.9_LordPE_1.41_Deluxe_b.zip)

Data-type reconstructor

* [ReClassEx](https://github.com/dude719/ReClassEx)
* [ReClass.NET](https://github.com/KN4CK3R/ReClass.NET) - port of ReClass to .NET

## Unpackers

* [FUU](https://github.com/crackinglandia/fuu) - [F]aster [U]niversal [U]npacker
* [TitanEngine](http://www.reversinglabs.com/products/TitanEngine.php)

## Obfuscators

Native

* [Stunnix](http://stunnix.com/prod/cxxo/)
* [M/o/Vfuscator](https://github.com/xoreaxeaxeax/movfuscator)

AutoIt scripts

* [Assembly Source Code Obfuscator](https://www.pelock.com/products/obfuscator)
* [AutoIt Source Code Obfuscator](https://www.pelock.com/products/autoit-obfuscator)

## Deobfuscators

Native

* [LLVM Deobfuscator](https://github.com/RPISEC/llvm-deobfuscator)
* [SATURN]() - software deobfuscation framework based on LLVM.

Java

* [Java Deobfuscator](https://javadeobfuscator.com/)

.NET

* [de4dot](https://github.com/0xd4d/de4dot)

Javascript

* [de4js](https://github.com/lelinhtinh/de4js)

PHP

* [evalhook](https://github.com/unreturned/evalhook)

String extraction

* [FLOSS](https://github.com/fireeye/flare-floss)
* [NoMoreXOR](https://github.com/hiddenillusion/NoMoreXOR)

## Binary Visualization

See also [Data & Format Reversing](_format.md).

* [Veles](https://codisec.com/veles/)
* [..cantor.dust..](https://sites.google.com/site/xxcantorxdustxx/home)
* [binglide](https://github.com/wapiflapi/binglide)

## Document Analysis

* [Ole Tools](http://www.decalage.info/python/oletools)
* [Didier's PDF Tools](http://blog.didierstevens.com/programs/pdf-tools/)
* [Origami](https://github.com/cogent/origami-pdf)

## Misc

- [bingrep](https://github.com/m4b/bingrep) - grep through binaries

- - - 

## IDA Script

* [IDA Python Src](https://github.com/idapython/src) - source code for IDAPython plugin, enable python script running in IDA Pro .

references

* [IDC Functions Doc](https://www.hex-rays.com/products/ida/support/idadoc/162.shtml)
* [Using IDAPython to Make your Life Easier](http://researchcenter.paloaltonetworks.com/tag/idapython/)
* [Introduction to IDA Python](https://tuts4you.com/download.php?view.3229)
* [The Beginner's Guide to IDA Python](https://leanpub.com/IDAPython-Book)
* [IDA Plugin Contest](https://www.hex-rays.com/contests/)

Script collection

* [fireeye/flare-ida](https://github.com/fireeye/flare-ida) - multiple IDA plugins and IDAPython scripts by FLARE team.
* [devttys0/ida](https://github.com/devttys0/ida) - collection of IDAPython plugins/scripts/modules.
* [onehawt IDA Plugin List](https://github.com/onethawt/idaplugins-list) - list of ida scripts (IDC / IDAPython), links to many repository.

## Ghidra Script

Script collection

* [ghidra ninja](https://github.com/ghidraninja/ghidra_scripts)
