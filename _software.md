# Awesome Software Reverse Engineering

A curated list of awesome reverse engineering resources to make you better! 

Managed by Reversing.ID for the reversing community.

## Table of Contents

- Resources
    - [Books](#books)
    - [Courses](#courses)
    - [Channels](#channels)
    - [Practices](#practices)
    - [References](#references)
- Tools
    - [Hex Editors](#hex-editors)
    - [Binary Format](#binary-format)
    - [Disassemblers](#disassemblers)
    - [Debuggers](#debuggers)
    - [Behavior Analysis](#behavior-analysis)
    - [Dynamic Binary Instrumentation](#dynamic-binary-instrumentation)
    - [Binary Analysis Framework](#binary-analysis-framework)
    - [Code Emulators](#code-emulators)
    - [Injector](#injectors)
    - [HTTP Intercept Proxy](#http-intercept-proxy)
    - [Import Reconstructors](#import-reconstructors)
    - [Scripting](#scripting)
    - [Unpackers](#unpackers)
    - [Obfuscators](#obfuscators)
    - [Deobfuscators](#deobfuscators)
    - [Binary Visualization](#binary-visualization)
    - [Document Analysis](#document-analysis)
    - [Misc](#misc)

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

* [Low-level Code Reference](https://github.com/ReversingID/LowLevelCode-Reference) - coming soon

Intermediate Representation

* [LLVM IR](https://llvm.org/docs/LangRef.html)
* [REIL](https://www.zynamics.com/binnavi/manual/html/reil_language.htm)
* [OpenREIL](https://github.com/Cr4sh/openreil)

- - - 

## Hex Editors

Hex editor lets you view/edit the binary data of a file.

Multi/cross platform

* [010 Editor](http://www.sweetscape.com/010editor/)
* [Kaitai Struct](https://kaitai.io)
* [wxHexEditor](https://www.wxhexeditor.org/)

Windows 

* [HxD](https://mh-nexus.de/en/hxd/)
* [Hex Workshop](http://www.hexworkshop.com/)
* [Hexinator](https://hexinator.com/)

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

Format parser

* [LIEF](https://lief.quarkslab.com/)

## Disassemblers & Decompilers

Native code disassembler and decompiler

* [Ghidra](https://ghidra-sre.org/)
* [IDA Pro](https://www.hex-rays.com/products/ida/index.shtml)
* [Binary Ninja](https://binary.ninja/)
* [Radare2](http://www.radare.org/r/) // [Cutter](https://cutter.re)
* [Hopper](http://hopperapp.com/)
* [Capstone](http://www.capstone-engine.org/)
* [fREedom](https://github.com/cseagle/fREedom)
* [Retdec](https://retdec.com/)
* [Snowman](https://derevenets.com/)
* [objdump](http://linux.die.net/man/1/objdump)
* [Medussa](https://github.com/wisk/medusa)
* [Plasma](https://github.com/joelpx/plasma)

Android application disassembler / decoder

* [JEB2](https://www.pnfsoftware.com/jeb2/)

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

Flash decompiler

* [JPEXS Flash Decompiler](https://www.free-decompiler.com/flash/)

Delphi decompiler

* [Interactive Delphi Reconstructor](https://github.com/crypto2011/IDR)

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

* [QIRA](http://qira.me/)
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

## Behavioral Analysis

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

* [DynamoRIO](http://www.dynamorio.org)
* [Frida](https://frida.re)
* [Pin](https://software.intel.com/en-us/articles/pin-a-dynamic-binary-instrumentation-tool)
* [QDBI](https://qbdi.quarkslab.com/)

## Binary Analysis Framework

* [Angr](http://angr.io/)
* [Triton](https://triton.quarkslab.com)
* [BAP](http://binaryanalysisplatform.github.io/)
* [BitBlaze](http://bitblaze.cs.berkeley.edu/)
* [PANDA](https://github.com/panda-re/panda)
* [BARF](https://github.com/programa-stic/barf-project)
* [S2E](https://s2e.systems/)
* [miasm](https://miasm.re/)
* [soot](https://github.com/Sable/soot) - Java optimization framework

Symbolic execution

* [KLEE](https://klee.github.io/)

Binary lifting

* [McSema](https://github.com/lifting-bits/mcsema)

Theorem prover and solver

* [Z3](https://github.com/Z3Prover/z3)
* [STP](https://stp.github.io/)
* [CVC4](https://cvc4.github.io/)
* [Boolector](https://boolector.github.io/)

## Code Emulators

* [unicorn](https://github.com/unicorn-engine/unicorn)
* [libemu](http://libemu.carnivore.it)
* [pegasus](https://github.com/imugee/pegasus)

## Injector

Windows

* [PolyHook](https://github.com/stevemk14ebr/PolyHook)
* [EasyHook](https://easyhook.github.io/)
* [Deviare2](https://github.com/nektra/Deviare2)

## HTTP Intercept Proxy

* [Fiddler](https://www.telerik.com/fiddler)
* [ZAP](https://www.owasp.org/index.php/OWASP_Zed_Attack_Proxy_Project)

## Import Reconstructors

* [ImpRec](http://www.woodmann.com/collaborative/tools/index.php/ImpREC)
* [Scylla](https://github.com/NtQuery/Scylla)
* [LordPE](http://www.woodmann.com/collaborative/tools/images/Bin_LordPE_2010-6-29_3.9_LordPE_1.41_Deluxe_b.zip)

## Scripting

* [IDA Python Src](https://github.com/idapython/src)
* [IDC Functions Doc](https://www.hex-rays.com/products/ida/support/idadoc/162.shtml)
* [Using IDAPython to Make your Life Easier](http://researchcenter.paloaltonetworks.com/tag/idapython/)
* [Introduction to IDA Python](https://tuts4you.com/download.php?view.3229)
* [The Beginner's Guide to IDA Python](https://leanpub.com/IDAPython-Book)
* [IDA Plugin Contest](https://www.hex-rays.com/contests/)
* [onehawt IDA Plugin List](https://github.com/onethawt/idaplugins-list)
* [pefile Python Libray](https://github.com/erocarrera/pefile)
* [ghidra ninja](https://github.com/ghidraninja/ghidra_scripts)

## Unpackers

* [FUU](https://github.com/crackinglandia/fuu) - [F]aster [U]niversal [U]npacker
* [TitanEngine](http://www.reversinglabs.com/products/TitanEngine.php)

## Obfuscator

Native

* [Stunnix](http://stunnix.com/prod/cxxo/)
* [M/o/Vfuscator](https://github.com/xoreaxeaxeax/movfuscator)

## Deobfuscators

Native

* [LLVM Deobfuscator](https://github.com/RPISEC/llvm-deobfuscator)
* [SATURN]()

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