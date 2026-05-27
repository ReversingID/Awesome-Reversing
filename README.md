# Awesome Reverse Engineering [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> A curated list of reverse engineering resources — books, courses, tools, and references — organized by domain.

Managed by [Reversing.ID](https://reversing.id) for the reversing community.

---

## Introduction

**Reverse Engineering** is the art and science of breaking something down, extracting the design and mechanics behind it, and understanding it at its basic principles — without access to the original design documentation.

> *Reversing is the process of, partially or fully, recovering the design, requirement specifications, and functions of a product from an analysis of its artifact.*

Reverse engineering is practiced across many disciplines: security research, malware analysis, vulnerability discovery, interoperability, archival preservation, and hardware teardowns. The skills, tools, and mental models differ significantly depending on *what* you are reversing.

### What makes this list different

Most awesome lists treat reverse engineering as a single topic. This list takes a different approach: **we split by domain**. Each domain has its own targets, toolchains, and body of knowledge. A firmware analyst and a database schema archaeologist are both doing reverse engineering, but their workflows share almost nothing.

This list is organized into **four domains**:

| Domain | What you're reversing | Typical goals |
|--------|-----------------------|---------------|
| [Software](software-reversing.md) | Executables, bytecode, libraries | Vulnerability research, malware analysis, crackmes, interoperability |
| [Hardware](hardware-reversing.md) | PCBs, ICs, embedded firmware | Teardowns, firmware extraction, protocol analysis, chip-level analysis |
| [Format](format-reversing.md) | File formats, network protocols, game assets | Parser construction, asset extraction, format documentation |
| [Database](database-reversing.md) | Flat-file, relational, and NoSQL databases | Schema recovery, data archaeology, remodelling |

---

## Domains

### [Software Reverse Engineering](software-reversing.md)

The most well-known domain. Targets are code in compiled form — native binaries (x86, ARM, RISC-V, …) or intermediate representations (JVM bytecode, .NET IL, WASM). Core workflow involves static analysis with disassemblers/decompilers and dynamic analysis with debuggers and instrumentation frameworks.

**Key tools:** IDA Pro, Ghidra, Binary Ninja, x64dbg, Frida, angr  
**Common use cases:** CTF challenges, malware analysis, vulnerability research, DRM analysis, game modding

### [Hardware Reverse Engineering](hardware-reversing.md)

Targets physical artifacts: circuit boards, integrated circuits, and embedded systems. Analysis spans from high-level board teardowns down to silicon-level circuit tracing. Firmware extraction is a common bridge between hardware and software reversing.

**Key tools:** Logic analyzers, oscilloscopes, JTAG/SWD debuggers, OpenOCD, Binwalk  
**Common use cases:** IoT security research, firmware extraction, protocol reverse engineering, chip decapping

### [Format Reverse Engineering](format-reversing.md)

Focuses on understanding the structure and semantics of binary data — how it is laid out, compressed, encrypted, or segmented. Frequently practiced in game modding communities where proprietary asset containers and undocumented formats are the norm.

**Key tools:** Hex editors (010 Editor, HexFiend), Kaitai Struct, ImHex, Wireshark  
**Common use cases:** Game asset extraction, protocol documentation, interoperability tooling, archive research

### [Database Reverse Engineering](database-reversing.md)

Targets structured data stores — flat-file databases (SQLite, MDB), relational schemas, and NoSQL collections. The goal is often schema recovery when documentation is missing, or remodelling when migrating between systems.

**Key tools:** DB schema visualizers, SQL clients, hex editors for flat-file formats  
**Common use cases:** Legacy system migration, undocumented DB schema recovery, forensic data archaeology

---

## Who is this for?

- **Security researchers and pentesters** looking for tooling and technique references
- **CTF players** building their reversing skill set across multiple categories
- **Malware analysts** needing a structured resource on software analysis tools
- **Embedded/IoT engineers** exploring hardware and firmware analysis
- **Game modders and archivists** working with proprietary formats and assets
- **Anyone curious** about how things work under the hood

---

## Contributing

Contributions are welcome. Please read [CONTRIBUTING.md](CONTRIBUTING.md) before submitting a pull request.

In short: make one PR per suggestion, keep descriptions concise, and add links to the bottom of the relevant category section in the appropriate domain file.
