# Awesome Apple Data Formats and Knowledge with stars

A collection of reverse engineered Apple formats, protocols, or other interesting bits.

[Join us on Discord](https://discord.gg/NAxRYvysuc) - [Discord Rules](https://hackdiffe.rent)

Repo inspired by [Papers we Love](https://github.com/papers-we-love/papers-we-love) ⭐ 108,807 | 🐛 3 | 🌐 Shell | 📅 2026-07-01

## Our Tooling Repos

### Our Homebrew Tap

Install our tap with `brew tap hack-different/homebrew-jailbreak`

Information about the maintaining of that tap can be found at [homebrew-jailbreak](http://hackdiffe.rent/homebrew-jailbreak/)

## Contributing and a warning

[Linking your Discord and GitHub](https://hackdiffe.rent/LINKING)

We want this collection to be around for new jailbreakers and hobbyists for years to come, so we must say: this
collection accepts (with gratitude) pull-requests that improve it, but under no circumstances
will a PR based on `AppleInternal`, or any other copyrighted works protected by the
[DMCA](https://en.wikipedia.org/wiki/Digital_Millennium_Copyright_Act) be accepted.  If
you need help determining this, tag the PR with `license help`, join the
[Discord server](https://discord.gg/hackdifferent), and ask a `#Legit` or higher role for help.

Violation of the DMCA or Copyright law is the responsibility of the submitter.

## Primary Data Source

We attempt to derive from machine sources and produce machine readable files (YAML) in this repo under `_data`.  For
information about creating and extending data format see [Data Format Guidance](docs/Data_Formats).

Updates and additions there should automatically be reflected in the documents

[`hack-different/apple-knowledge/_data`](https://github.com/hack-different/apple-knowledge/tree/main/_data) ⭐ 1,370 | 🐛 4 | 🌐 Ruby | 📅 2026-08-16

Another authoritative source of information is the open source code released by Apple themselves at one of the
following locations:

* [Open Source at Apple Wesbite](https://opensource.apple.com)
* [Apple's GitHub profile](https://github.com/apple)
* [apple-oss-distributions's Github profile](https://github.com/apple-oss-distributions)
* [Apple Gifts](docs/GIFTS)

## Tools

### Libraries for Binary Analysis and Modification

See [docs/Binary\_Tooling](docs/Binary_Tooling)

### Tools for Binary Analysis and Modification

* [Unicorn Engine](https://github.com/unicorn-engine/unicorn) ⭐ 9,238 | 🐛 211 | 🌐 C | 📅 2026-07-30
* [Capstone Engine](https://github.com/aquynh/capstone) ⭐ 8,957 | 🐛 362 | 🌐 C | 📅 2026-08-13
* [`blacktop/ipsw`](https://github.com/blacktop/ipsw) ⭐ 3,648 | 🐛 7 | 🌐 Go | 📅 2026-08-18
* [`alephsecurity/xnu-qemu-arm64`](https://github.com/alephsecurity/xnu-qemu-arm64) ⭐ 1,461 | 🐛 20 | 🌐 C | 📅 2021-09-16
  * [Build iOS on QEMU](https://github.com/alephsecurity/xnu-qemu-arm64/wiki/Build-iOS-on-QEMU) ⭐ 1,461 | 🐛 20 | 🌐 C | 📅 2021-09-16
  * [`alephsecurity/xnu-qemu-arm64-tools`](https://github.com/alephsecurity/xnu-qemu-arm64-tools) ⭐ 181 | 🐛 13 | 🌐 C | 📅 2021-02-21
* [ktool](https://github.com/cxnder/ktool) ⭐ 524 | 🐛 16 | 🌐 Python | 📅 2026-03-07 - FOSS Python Mach-O Tool
* [`checkra1n/toolchain`](https://github.com/checkra1n/toolchain) ⭐ 96 | 🐛 0 | 🌐 C++ | 📅 2022-01-28
* [mootool](https://github.com/hack-different/mootool) ⭐ 13 | 🐛 1 | 🌐 Ruby | 📅 2026-08-13 - FOSS Ruby Mach-O Tool (aims to replicate jtool2 feature set)
* [IDA Disassembler by Hex-Rays](https://hex-rays.com/ida-pro/)
  * [`onethawt/idaplugins-list`](https://github.com/onethawt/idaplugins-list) ⭐ 3,834 | 🐛 8 | 📅 2024-05-31
  * [`Cisco-Talos/GhIDA`](https://github.com/Cisco-Talos/GhIDA) ⭐ 816 | 🐛 13 | 🌐 Python | 📅 2021-02-19
  * [`avast/retdec-idaplugin`](https://github.com/avast/retdec-idaplugin) ⭐ 799 | 🐛 14 | 🌐 C++ | 📅 2025-02-03
  * [`cellebrite-srl/FunctionInliner`](https://github.com/cellebrite-srl/FunctionInliner) ⭐ 229 | 🐛 0 | 🌐 C | 📅 2024-12-31
  * [`matteyeux/ida-iboot-loader`](https://github.com/matteyeux/ida-iboot-loader) ⭐ 172 | 🐛 0 | 🌐 Python | 📅 2024-11-02
  * [`cellebrite-srl/PacExplorer`](https://github.com/cellebrite-srl/PacXplorer) ⭐ 158 | 🐛 1 | 🌐 Python | 📅 2026-05-27
  * [`cellebrite-srl/ida_kernelcache`](https://github.com/cellebrite-srl/ida_kernelcache) ⭐ 149 | 🐛 0 | 🌐 Python | 📅 2026-08-12
  * [`hack-different/iBoot-IDA`](https://github.com/hack-different/iBoot-IDA) ⚠️ Archived
  * [`haiyuidesu/sephelper`](https://github.com/haiyuidesu/sephelper) ⭐ 36 | 🐛 0 | 🌐 Python | 📅 2025-08-26
* [Binary Ninja Disassembler](https://binary.ninja)
  * [`cxnder/bn-dyldsharedcache`](https://github.com/cxnder/bn-dyldsharedcache) ⭐ 92 | 🐛 7 | 🌐 Python | 📅 2026-02-25
  * [`jonpalmisc/ObjectiveNinja`](https://github.com/jonpalmisc/ObjectiveNinja) ⚠️ Archived
  * [`matteyeux/seprom-loader`](https://github.com/matteyeux/seprom-loader/) ⭐ 61 | 🐛 1 | 🌐 Python | 📅 2025-09-07
  * [`skr0x1c0/binja_kc`](https://github.com/skr0x1c0/binja_kc) ⭐ 39 | 🐛 0 | 🌐 C++ | 📅 2025-03-23
  * [`EliseZeroTwo/iBoot-Binja-Loader`](https://github.com/EliseZeroTwo/iBoot-Binja-Loader/) ⭐ 35 | 🐛 0 | 🌐 Python | 📅 2023-02-24
* [VisUAL ARM Simulator](https://salmanarif.bitbucket.io/visual/index.html)
* [Ghidra Disassembler](https://ghidra-sre.org)
  * [`AllsafeCyberSecurity/awesome-ghidra`](https://github.com/AllsafeCyberSecurity/awesome-ghidra) ⭐ 1,425 | 🐛 3 | 📅 2026-06-18
  * [`0x36/ghidra_kernelcache`](https://github.com/0x36/ghidra_kernelcache) ⭐ 370 | 🐛 8 | 🌐 Python | 📅 2022-11-06
* [Hopper Disassembler](https://www.hopperapp.com)
* [QEMU](https://qemu.readthedocs.io/en/latest/)
  * [`geohot/qira`](https://github.com/geohot/qira) ⭐ 4,069 | 🐛 69 | 🌐 C | 📅 2022-07-02
  * [QEMU Apple Branch](https://github.com/TrungNguyen1909/qemu-t8030) ⚠️ Archived
* [jtool2](https://www.newosxbook.com/tools/jtool.html)
* [frida](https://frida.re)

## Guides and General

* [OWASP: iOS Tampering and Reverse Engineering](https://github.com/OWASP/owasp-mstg/blob/master/Document/0x06c-Reverse-Engineering-and-Tampering.md) ⭐ 13,119 | 🐛 231 | 🌐 Python | 📅 2026-08-14
* [kpwn / qwertyoruiop's Wiki](https://github.com/kpwn/iOSRE/tree/master/wiki) ⭐ 1,180 | 🐛 0 | 🌐 Shell | 📅 2018-06-30
* [kpwn / qwertyoruiop's Papers](https://github.com/kpwn/iOSRE/tree/master/resources/papers) ⭐ 1,180 | 🐛 0 | 🌐 Shell | 📅 2018-06-30
* [`Proteas/apple-cve`](https://github.com/Proteas/apple-cve) ⭐ 173 | 🐛 0 | 📅 2026-08-10
* [About Apple Prototype and CPFM](docs/Prototypes)
* [Kernel Debug Kit](docs/KDK)
* [\*OS Internals by Jonathan Levin](http://newosxbook.com/index.php)
* [T2 Dev Setup](docs/T2)
* [Apple 4CC](docs/4CC)
* [`bytepack/IntroToiOSReverseEngineering`](https://github.com/bytepack/IntroToiOSReverseEngineering)
* [Remote Attack Surface](https://googleprojectzero.blogspot.com/2019/08/the-fully-remote-attack-surface-of.html)
* [Lakr233's Research](https://lab.qaq.wiki/Lakr233/iOS-kernel-research/-/tree/master)

## Devices

* [Device List](docs/Devices)
* T2
  * [`t2linux/apple-bce-drv`](https://github.com/t2linux/apple-bce-drv) ⭐ 102 | 🐛 3 | 🌐 C | 📅 2026-06-24
  * [T2 Dev Team: `t8012` / Apple T2 / bridgeOS](https://t8012.dev)
  * [Duo Labs: Apple T2 XPC](https://duo.com/labs/research/apple-t2-xpc)
* Wi-Fi / Bluetooth
  * [`seemoo-lab/internalblue`](https://github.com/seemoo-lab/internalblue) ⭐ 785 | 🐛 21 | 🌐 Python | 📅 2024-08-21
  * [`seemoo-lab/frankenstein`](https://github.com/seemoo-lab/frankenstein) ⭐ 465 | 🐛 8 | 🌐 C | 📅 2024-02-07
* [The iPhone Wiki](https://www.theiphonewiki.com/wiki/Main_Page)
* SMC (System Management Controller) for pre-T2
  * [`acidanthera/VirtualSMC`](https://github.com/acidanthera/VirtualSMC) ⭐ 1,795 | 🐛 0 | 🌐 C++ | 📅 2026-04-09
  * [`t8012/smcutil`](https://github.com/t8012/smcutil) ⭐ 47 | 🐛 0 | 🌐 Ruby | 📅 2022-02-18 - Create SMC binaries from update payloads

## Kernel General

* [`acidanthera/Lilu`](https://github.com/acidanthera/Lilu) ⭐ 3,852 | 🐛 0 | 🌐 C | 📅 2026-03-20
* [`osy/AMFIExemption`](https://github.com/osy/AMFIExemption) ⭐ 124 | 🐛 0 | 🌐 C++ | 📅 2020-09-13
* [Mach](https://developer.apple.com/library/content/documentation/Darwin/Conceptual/KernelProgramming/Mach/Mach.html)
  * [Apple's XNU Tarballs](https://opensource.apple.com/tarballs/xnu/)
* [Mach and the Mach Interface Generator by nemo](https://www.exploit-db.com/papers/13176/)
* [Apple IPC by Ian Beer](https://thecyberwire.com/events/docs/IanBeer_JSS_Slides.pdf)
* [Siguza's Research on KTRR](https://blog.siguza.net/KTRR/)
* [Tick Tock by xerub](https://xerub.github.io/ios/kpp/2017/04/13/tick-tock.html)
* [Casa de PPL by Levin](http://newosxbook.com/articles/CasaDePPL.html)
* [KTRW by Brandon Azad](https://googleprojectzero.blogspot.com/2019/10/ktrw-journey-to-build-debuggable-iphone.html)
* [Qwertyoruiopz Attacking XNU: Part 1](https://web.archive.org/web/20160131061526/http://blog.qwertyoruiop.com/?p=38)
* [Qwertyoruiopz Attacking XNU: Part 2](https://web.archive.org/web/20160131061526/http://blog.qwertyoruiop.com/?p=48)
* [Kernel Heap by Stefan Esser](http://gsec.hitb.org/materials/sg2016/D2%20-%20Stefan%20Esser%20-%20iOS%2010%20Kernel%20Heap%20Revisited.pdf)
* [Levin's Who needs `task_for_pid()` anyway...](https://newosxbook.com/articles/PST2.html)
* Apple Official Documentation
  * [Kernel Programming Guide](https://developer.apple.com/library/content/documentation/Darwin/Conceptual/KernelProgramming)
  * [IOKit Fundamentals](https://developer.apple.com/library/content/documentation/DeviceDrivers/Conceptual/IOKitFundamentals)
  * [Virtual Memory System](https://developer.apple.com/library/content/documentation/Performance/Conceptual/ManagingMemory/Articles/AboutMemory.html)

## Protocols / Formats

### Bootloader Related

* EFI
  * [`EFI`](docs/EFI)
* [`NVRAM`](docs/NVRAM)
  * [NVRAM unlock](https://stek29.rocks/2018/06/26/nvram.html)
* [`SEP_memmap`](docs/SEP_memmap)
* [All About Kernels](docs/Kernels)
  * [`apple/darwin-xnu`](https://github.com/apple/darwin-xnu) ⚠️ Archived
* [`Factory_Firmware_Payloads`](docs/Factory_Firmware_Payloads)
* iBoot
  * [`OpenJailbreak/iBootRE`](https://github.com/OpenJailbreak/iBootRE) ⭐ 19 | 🐛 0 | 🌐 C | 📅 2018-10-25
  * [iBoot Firebloom](https://saaramar.github.io/iBoot_firebloom/)
  * [\*OS iBoot](https://newosxbook.com/bonus/iBoot.pdf)
* SecureROM
  * [SecureROM Binaries](https://github.com/hekapooios/hekapooios.github.io/tree/master/resources/APROM) ⭐ 34 | 🐛 3 | 🌐 JavaScript | 📅 2026-08-05
* TXM - Trusted eXecutation Monitor
  * [TXM & SPTM](https://www.df-f.com/blog/ios17)

### Archive / Disk Formats

* APFS - Apple Filesystem
  * [`sgan81/apfs-fuse`](https://github.com/sgan81/apfs-fuse) ⭐ 2,135 | 🐛 124 | 🌐 C++ | 📅 2024-08-13
  * [`libyal/libfsapfs`](https://github.com/libyal/libfsapfs) ⭐ 418 | 🐛 8 | 🌐 C | 📅 2026-08-04
  * [`cugu/apfs.ksy`](https://github.com/cugu/apfs.ksy) ⚠️ Archived
  * [Apple APFS Reference](https://developer.apple.com/support/downloads/Apple-File-System-Reference.pdf)
  * [bxl1989 APFS Remount](https://bxl1989.github.io/2019/01/17/apfs-remount.html)
* [LwVM Lightweight Volume Manager](https://stek29.rocks/2018/01/22/lwvm-mapforio.html)
* NeXT / Apple "Bill of Materials" / `pkg` / `bom`
  * [`iineva/bom`](https://github.com/iineva/bom) ⭐ 18 | 🐛 0 | 🌐 Go | 📅 2025-02-26
* `pbzx`
* Apple Disk Image - `dmg`
  * [`darlinghq/darling-dmg`](https://github.com/darlinghq/darling-dmg) ⭐ 302 | 🐛 22 | 🌐 C++ | 📅 2025-10-18
  * [`nlitsme/encrypteddmg`](https://github.com/nlitsme/encrypteddmg) ⭐ 44 | 🐛 2 | 🌐 Python | 📅 2023-08-22
  * [`jhermsmeier/node-udif`](https://github.com/jhermsmeier/node-udif)
* Signed System Volumes (SSV) / `root_hash`

### Databases / Serialization

* Property Lists
  * [`libimobiledevice/libplist`](https://github.com/libimobiledevice/libplist) ⭐ 632 | 🐛 31 | 🌐 C | 📅 2026-05-22
* iTunes database
  * [`josephw/titl`](https://github.com/josephw/titl) ⭐ 66 | 🐛 22 | 🌐 Java | 📅 2024-03-27
  * [`jeanthom/libitlp`](https://github.com/jeanthom/libitlp) ⚠️ Archived
  * <https://metacpan.org/pod/Mac::iTunes::Library::Parse>
* Apple iDevice Backup Format
  * [`horrorho/InflatableDonkey`](https://github.com/horrorho/InflatableDonkey) ⭐ 268 | 🐛 55 | 🌐 Java | 📅 2022-11-16
  * [`rickmark/libibackup`](https://github.com/rickmark/libibackup) ⭐ 16 | 🐛 2 | 🌐 C | 📅 2026-08-14

### Image, Sound and Other Resources

* [Apple Flavored PNG](docs/PNG)
* [Apple IMA ADPCM](https://wiki.multimedia.cx/index.php?title=Apple_QuickTime_IMA_ADPC)
  * [Using a Custom Startup Sound on a Power Macintosh G3 Blue and White](https://www.downtowndougbrown.com/2012/07/power-macintosh-g3-blue-and-white-custom-startup-sound/)
* AirPlay2
  * [`mikebrady/shareport-sync`](https://github.com/mikebrady/shairport-sync) ⭐ 8,815 | 🐛 17 | 🌐 C | 📅 2026-08-09

### Software Update / Installers

* [Mobile Asset URLs](docs/Mobile_Assets)
* [`notpeter/apple-installer-checksums`](https://github.com/notpeter/apple-installer-checksums) ⚠️ Archived
* [ipsw.me](https://ipsw.me)
* [ipswbeta.dev](https://ipswbeta.dev)

### Code and Signature Formats

* [Mach-O File Types](docs/MachO.md) - Mach-O / Signing / Entitlements
  * [`ProcursusTeam/ldid`](https://github.com/ProcursusTeam/ldid) ⭐ 272 | 🐛 2 | 🌐 C++ | 📅 2026-07-24 - Alternative to sbingner/ldid with
    some updates for iOS 15 and general fixes
  * [`sbingner/ldid`](https://github.com/sbingner/ldid) ⭐ 55 | 🐛 4 | 🌐 C++ | 📅 2022-03-12 - Codesign tool
  * [Apple CTF / Compact Type Format](https://github.com/apple-oss-distributions/dtrace/tree/main/tools/ctfconvert) ⭐ 25 | 🐛 0 | 🌐 C | 📅 2025-10-22
  * [m4b Mach Binaries](http://www.m4b.io/reverse/engineering/mach/binaries/2015/03/29/mach-binaries.html)
  * [J's Entitlements Database](https://newosxbook.com/ent.jl)
  * [Levin's Code Signing](http://www.newosxbook.com/articles/CodeSigning.pdf)
* img4 - Apple signed images, version 4
  * [`xerub/img4lib`](https://github.com/xerub/img4lib) ⭐ 369 | 🐛 6 | 🌐 C | 📅 2023-02-11
  * [`tihmstar/img4tool`](https://github.com/tihmstar/img4tool) ⭐ 327 | 🐛 2 | 🌐 C++ | 📅 2026-01-29
  * [`m1stadev/PyIMG4`](https://github.com/m1stadev/PyIMG4) ⭐ 67 | 🐛 15 | 🌐 Python | 📅 2026-08-17 - A Python library/CLI tool for parsing IMG4
  * [`h3adshotzz/img4helper`](https://github.com/h3adshotzz/img4helper) ⚠️ Archived
  * [TheiPhoneWiki's documentation on IMG4 files](https://www.theiphonewiki.com/wiki/IMG4_File_Format)
* TrustCache - Pre-authorized Binary Hashes
  * [`CRKatri/trustcache`](https://github.com/CRKatri/trustcache) ⭐ 49 | 🐛 0 | 🌐 C | 📅 2023-02-12
  * [`t8012/go-aapl-integrity`](https://github.com/t8012/go-aapl-integrity) ⭐ 10 | 🐛 1 | 🌐 Go | 📅 2020-10-27
  * [Apple Platform Security - Trust caches](https://support.apple.com/guide/security/trust-caches-sec7d38fbf97/web)
* EALF - `eficheck` baselines
  * [`t8012/efivalidate`](https://github.com/t8012/efivalidate) ⭐ 25 | 🐛 1 | 🌐 Ruby | 📅 2022-02-18
  * [`t8012/go-aapl-integrity`](https://github.com/t8012/go-aapl-integrity) ⭐ 10 | 🐛 1 | 🌐 Go | 📅 2020-10-27
  * [`EALF`](docs/EALF)
* ChunkList - Used to verify macOS Recovery / Internet Recovery
  * [`t8012/go-aapl-integrity`](https://github.com/t8012/go-aapl-integrity) ⭐ 10 | 🐛 1 | 🌐 Go | 📅 2020-10-27
* `dyld` and DSC (dyld Shared Cache)
  * [`arandomdev/DyldExtractor`](https://github.com/arandomdev/DyldExtractor) ⚠️ Archived - Fixes up linking
  * [`rickmark/yolo_dsc`](https://github.com/rickmark/yolo_dsc) ⭐ 15 | 🐛 1 | 🌐 C | 📅 2022-02-13 - Used as last resort and depend on Xcode
  * [Levin's Dyld](http://www.newosxbook.com/articles/DYLD.html)
  * [dyld\_shared\_cache\_util.cpp](https://opensource.apple.com/source/dyld/dyld-195.5/launch-cache/dyld_shared_cache_util.cpp.auto.html)
* iBoot LocalPolicy, RemotePolicy and BAA signing
  * [`M1_Boot_Policy`](docs/M1_Boot_Policy)
* Rosetta2
  * [ProjectChampollion](https://github.com/FFRI/ProjectChampollion/) ⚠️ Archived
* Swift
  * [Swift Mangling](https://github.com/apple/swift/blob/main/docs/ABI/Mangling.rst) ⭐ 70,256 | 🐛 9,203 | 🌐 Swift | 📅 2026-08-18

### Sandbox or 'Seatbelt'

* [Levin's - The Apple Sandbox](http://newosxbook.com/files/HITSB.pdf)
* [Apple Sandbox Guide v1.0](https://reverse.put.as/wp-content/uploads/2011/09/Apple-Sandbox-Guide-v1.0.pdf)
* [OWASP - Reversing the Apple Sandbox](https://owasp.org/www-pdf-archive/OWASP_-_EEE_2015_-_Reversing_the_Apple_Sandbox.pdf)
* [iBSparkles Breaking Entitlements](https://sparkes.zone/blog/ios/2018/04/06/diving-into-the-kernel-entitlements.html)
* [stek29: Shenanigans, Shenanigans!](https://stek29.rocks/2018/12/11/shenanigans.html)
* [argp vs com.apple.security.sandbox](https://census-labs.com/media/sandbox-argp-csw2019-public.pdf)
* [`malus-security/sandblaster`](https://github.com/malus-security/sandblaster) ⭐ 268 | 🐛 6 | 🌐 Python | 📅 2025-04-24

### Secure Enclave Processor

* [Attack Secure Boot of SEP - blackbird](https://github.com/windknown/presentations/blob/master/Attack_Secure_Boot_of_SEP.pdf) ⭐ 72 | 🐛 0 | 📅 2020-08-06
* [`justtryingthingsout/sepsplit-rs`](https://github.com/justtryingthingsout/sepsplit-rs) ⭐ 48 | 🐛 1 | 🌐 Rust | 📅 2026-06-10
* [SEPROM](https://github.com/hekapooios/hekapooios.github.io/tree/master/resources/SEPROM) ⭐ 34 | 🐛 3 | 🌐 JavaScript | 📅 2026-08-05
* [`nyuszika7h/sepfinder`](https://github.com/nyuszika7h/sepfinder) ⚠️ Archived
* [SEP\_memmap](docs/SEP_memmap)
* [sep.yaml](_data/sep.yaml)
* [Demystifying the Secure Enclave Processor](https://www.blackhat.com/docs/us-16/materials/us-16-Mandt-Demystifying-The-Secure-Enclave-Processor.pdf)
  * [Mirror of presentation](http://mista.nu/research/sep-paper.pdf?_x_tr_sch=http&_x_tr_sl=auto&_x_tr_tl=en&_x_tr_hl=en-US)
* [`seputil`](https://www.theiphonewiki.com/wiki/Seputil)
  * [`mwpcheung/AppleSEPFirmware`](https://github.com/mwpcheung/AppleSEPFirmware) ⭐ 59 | 🐛 0 | 📅 2020-03-31
* [SEPOS: A Guided Tour](https://data.hackinn.com/ppt/2018腾讯安全国际技术峰会/SEPOS：A%20Guided%20Tour.pdf)
* [iPhone Data Protection in Depth](https://www.slideshare.net/seguridadapple/iphone-data-protection-in-depth)
* [Overcoming iPhone Data Protection](https://www.slideshare.net/andrey.belenko/ios-forensics-overcoming-iphone-data-protection)

### ARM / x86

* ARM General
  * [Siguza's ARM Bootcamp](https://github.com/Siguza/ios-resources/blob/master/bits/arm64.md) ⭐ 1,964 | 🐛 4 | 📅 2025-05-24
  * [ARMv8 Overview](https://www.element14.com/community/servlet/JiveServlet/previewBody/41836-102-1-229511/ARM.Reference_Manual.pdf)
  * [ARMv8 ARM ARM (Architecture Reference Manual)](https://developer.arm.com/docs/ddi0487/latest)
  * [ARMv8-A Tools](https://developer.arm.com/products/architecture/cpu-architecture/a-profile/exploration-tools)
  * [ARM Software Standards](https://developer.arm.com/architectures/system-architectures/software-standards)
* Apple CPUs
  * [Asahi: Introduction to Apple Silicon](https://github.com/AsahiLinux/docs/wiki/Introduction-to-Apple-Silicon) ⭐ 2,249 | 🐛 20 | 🌐 HTML | 📅 2026-08-02
  * [dougallj's applecpu](https://dougallj.github.io/applecpu/firestorm.html)
* Compilers
  * [ARM Clang PAC ABI](https://github.com/apple/llvm-project/blob/apple/main/clang/docs/PointerAuthentication.rst) ⭐ 1,239 | 🐛 610 | 🌐 LLVM | 📅 2026-08-18
* ARM Mitigations
  * [APRR](https://blog.siguza.net/APRR/)
  * [PAN](https://blog.siguza.net/PAN/)
  * [SPRR & GXF](https://blog.svenpeter.dev/posts/m1_sprr_gxf/)

### Hypervisor / Virtualization

* Apple Hypervisor
  * [Official documentation](https://developer.apple.com/documentation/hypervisor)
  * [Hypervisor on Apple Silicon](https://developer.apple.com/documentation/hypervisor/apple_silicon)

## Baseband

* `baseband.yaml` in Data Files
* Qualcomm
  * [`hack-different/apple-baseband`](https://github.com/hack-different/apple-baseband) ⭐ 15 | 🐛 0 | 🌐 Python | 📅 2022-09-17
  * Hexagon DSP
    * [Hexagon SDK](https://developer.qualcomm.com/software/hexagon-dsp-sdk)
    * [Hexagon QEMU](https://github.com/Comsecuris/qemu-hexagon) ⭐ 34 | 🐛 1 | 🌐 C | 📅 2019-10-04
    * [Binary Ninja Hexagon](https://github.com/google/binja-hexagon) ⚠️ Archived
    * [Hexag00n](https://github.com/programa-stic/hexag00n) ⭐ 119 | 🐛 3 | 🌐 Python | 📅 2017-01-23
    * [IDA Hexagon](https://github.com/gsmk/hexagon) ⭐ 241 | 🐛 1 | 🌐 C | 📅 2025-04-07
    * [idp\_heaxagon](https://github.com/n-o-o-n/idp_hexagon) ⭐ 137 | 🐛 0 | 🌐 C++ | 📅 2026-05-19

### Coprocessors

* [hollance/neural-engine](https://github.com/hollance/neural-engine) ⭐ 2,517 | 🐛 10 | 📅 2026-03-12
* RTKit - "Realtime" Kit
  * [19h/ftab-dump](https://github.com/19h/ftab-dump) ⭐ 72 | 🐛 0 | 🌐 Rust | 📅 2026-06-03

### USB / Wired Protocols / Low Level Hardware

* [`gh2o/rvi_capture`](https://github.com/gh2o/rvi_capture) ⭐ 216 | 🐛 2 | 🌐 Python | 📅 2024-03-26
* [`osy/ThunderboltPatcher`](https://github.com/osy/ThunderboltPatcher) ⭐ 106 | 🐛 2 | 🌐 Objective-C | 📅 2019-11-11
* Basically all iDevice / iTunes
  * [`libimobiledevice/libimobiledevice`](https://github.com/libimobiledevice/libimobiledevice) ⭐ 8,112 | 🐛 848 | 🌐 C | 📅 2026-06-10
  * [`doronz88/pymobiledevice3`](https://github.com/doronz88/pymobiledevice3) ⭐ 2,640 | 🐛 41 | 🌐 Python | 📅 2026-08-18
  * [`hack-different/python-libimobiledevice`](https://github.com/hack-different/python-libimobiledevice) ⭐ 11 | 🐛 0 | 🌐 Python | 📅 2022-02-16
  * [libimobiledevice.org](https://libimobiledevice.org)
* DFU / Recovery
  * [`libimoibledevice/libirecovery`](https://github.com/libimobiledevice/libirecovery) ⭐ 649 | 🐛 49 | 🌐 C | 📅 2026-08-04
  * [Technical analysis of the checkm8 exploit](https://habr.com/en/company/dsec/blog/472762/)
* usbmuxd - USB transport for iDevices
  * [`libimobiledevice/usbmuxd`](https://github.com/libimobiledevice/usbmuxd) ⭐ 1,749 | 🐛 117 | 🌐 C | 📅 2025-12-06
  * [`t8012/demuxusb`](https://github.com/t8012/demuxusb) ⭐ 35 | 🐛 0 | 🌐 C++ | 📅 2026-08-14
* `com.apple.restored` - iDevice Restore Protocol
  * [`libimobiledevice/idevicerestore`](https://github.com/libimobiledevice/idevicerestore) ⭐ 1,912 | 🐛 331 | 🌐 C | 📅 2026-06-26
* UTDM - USB Target Disk Mode
  * [`rickmark/apple_utdm`](https://github.com/rickmark/apple_utdm) ⭐ 9 | 🐛 0 | 🌐 C | 📅 2020-02-27
* USB-C Power Delivery - Vendor Defined Messages
  * [`rickmark/macvdmtool`](https://github.com/rickmark/macvdmtool) ⭐ 4 | 🐛 0 | 🌐 C++ | 📅 2025-09-05
  * [USB-C Port Controller (ACE) Secrets](https://blog.t8012.dev/ace-part-1/)
* Lightning
  * [http://ramtin-amin.fr/#tristar](https://web.archive.org/web/20220107101537/http://ramtin-amin.fr/tristar.html)
  * <https://nyansatan.github.io/lightning/>
* NVMe / NAND / PCIe
  * <http://ramtin-amin.fr/#nvmepcie>
  * <http://ramtin-amin.fr/#nvmedma>
* [Qi Wireless Charging](https://www.wirelesspowerconsortium.com/knowledge-base/specifications/download-the-qi-specifications.html)

### Network / Wireless / Transit

* Apple Wi-Fi Password Sharing
  * [`seemoo-lab/openwifipass`](https://github.com/seemoo-lab/openwifipass) ⭐ 835 | 🐛 3 | 🌐 Python | 📅 2026-08-17
* AWDL - Apple Wireless Distribution Link
  * [Findings from Ian Beer, Project Zero](https://googleprojectzero.blogspot.com/2020/12/an-ios-zero-click-radio-proximity.html)
* Bluetooth Bonjour (Service Discovery)
* iCloud
  * [nicolas17/mesu-archive](https://gitlab.com/nicolas17/mesu-archive)
* Apple Watch Pairing
* `com.apple.terminusd`
* [Magic Pairing: Securing Bluetooth Peripherals](https://arxiv.org/pdf/2005.07255.pdf)
* ATC - Air Traffic Control - iTunes Wi-Fi Sync
* RemoteXPC
  * <https://duo.com/labs/research/apple-t2-xpc>
  * [XPoCe](http://newosxbook.com/tools/XPoCe2.html)
* macOS Internet Recovery
  * [`rickmark/apple_net_recovery`](https://github.com/rickmark/apple_net_recovery) ⭐ 14 | 🐛 0 | 🌐 Ruby | 📅 2020-10-25
  * [`Internet Recovery`](docs/Internet_Recovery)
* [iCloud Keychain](https://www.theiphonewiki.com/wiki/ICloud_Keychain) (Umbrella for multiple formats)

### System Configuration and State

* FDR - Factory Data Restore
* SysCfg - System Configuration - Serial Number and other Device Info
* APTicket - The root of an authorized version set

### Diagnostic Protocols

* AWDD - Apple Wireless Diagnostics (misnomer, more than wireless, system trace)
  * [`rickmark/awdd_decode`](https://github.com/rickmark/awdd_decode) ⭐ 17 | 🐛 0 | 🌐 Python | 📅 2022-07-30
* Mojo Serial
  * [MojoKDP.kext.S](https://github.com/rickmark/mojo_thor/blob/master/MojoKDP/mojo.kext.S) ⭐ 65 | 🐛 0 | 🌐 Assembly | 📅 2026-07-22
* Apple "tailspin"
* Apple `tracev3` Unified Logging
  * [dtformats](https://github.com/libyal/dtformats/blob/main/documentation/Apple%20Unified%20Logging%20and%20Activity%20Tracing%20formats.asciidoc) ⭐ 197 | 🐛 10 | 🌐 Python | 📅 2026-07-04
  * [\`ydkhatri/UnifiedLogReader\`\`](https://github.com/ydkhatri/UnifiedLogReader) ⭐ 100 | 🐛 2 | 🌐 Python | 📅 2025-07-25
* XHC20 USB Capture
  * [`hack-different/demuxusb/ext/pcapng.h`](https://github.com/t8012/demuxusb/blob/b6b1a1a6633449c2cb16ad44edcc22aab4dc29cd/ext/pcapng.h) ⭐ 35 | 🐛 0 | 🌐 C++ | 📅 2026-08-14

## Jailbreaks

* [`axi0mX/ipwndfu`](https://github.com/axi0mX/ipwndfu) ⭐ 7,391 | 🐛 168 | 🌐 Python | 📅 2024-02-21
* [Fugu14 writeup](https://github.com/LinusHenze/Fugu14/blob/master/Writeup.pdf) ⚠️ Archived
* [`LinusHenze/Fugu`](https://github.com/LinusHenze/Fugu) ⚠️ Archived
* [rootlessJB writeup](https://github.com/jakeajames/rootlessJB3/blob/master/writeup.pdf) ⭐ 362 | 🐛 32 | 🌐 C | 📅 2019-07-26
* [`0x7ff/gaster`](https://github.com/0x7ff/gaster) ⭐ 218 | 🐛 8 | 🌐 C | 📅 2023-02-02
* [limera1n](https://github.com/Chronic-Dev/syringe/blob/master/syringe/exploits/limera1n/limera1n.c) ⭐ 188 | 🐛 4 | 🌐 C | 📅 2021-08-21
* [`dora2-iOS/ipwnder_lite`](https://github.com/dora2-iOS/ipwnder_lite) ⚠️ Archived
* [`OpenJailbreak/greenpois0n`](https://github.com/OpenJailbreak/greenpois0n) ⭐ 46 | 🐛 0 | 🌐 Objective-C | 📅 2017-08-20
* [checkra1n](https://checkra.in)
  * [checkra1n 1337](https://checkra.in/1337)
* [unc0ver](https://unc0ver.dev)
* [Taurine](https://taurine.app)
* [Odyssey](https://theodyssey.dev/)
* [Chimera](https://chimera.coolstar.org/)
* [palera1n](https://palera.in/)
* [evasi0n writeup by geohot](http://geohot.com/e7writeup.html)
* TaIG
  * [8.0](http://www.newosxbook.com/articles/TaiG.html)
  * [8.1.2](http://www.newosxbook.com/articles/TaiG2.html)
  * [8.1.3](http://www.newosxbook.com/articles/28DaysLater.html)
  * [8.4](http://www.newosxbook.com/articles/HIDeAndSeek.html)

### Jailbreak Tooling

* [`ProcursusTeam/Procursus`](https://github.com/ProcursusTeam/Procursus) ⭐ 1,001 | 🐛 150 | 🌐 Makefile | 📅 2026-08-01
* [ElleKit](https://github.com/evelyneee/ellekit) ⭐ 697 | 🐛 11 | 🌐 Swift | 📅 2026-07-31
* [`comex/substitute`](https://github.com/comex/substitute) ⭐ 586 | 🐛 10 | 🌐 C | 📅 2019-09-01
* [`Chronic-Dev/syringe`](https://github.com/Chronic-Dev/syringe) ⭐ 188 | 🐛 4 | 🌐 C | 📅 2021-08-21
* [`sbingner/substitute`](https://github.com/sbingner/substitute) ⭐ 108 | 🐛 0 | 🌐 C | 📅 2025-02-26
* [Cydia](https://cydia.saurik.com)
* [Zebra](https://getzbra.com/)
* [Sileo](https://getsileo.app/)

### Jailbreak Slides

* [Jailbreaking iOS in the Post-Apocalyptic Age](https://cameronkatri.com/nullcongoa2022.pdf)
* [Fugu15 Slides](https://objectivebythesea.org/v5/talks/OBTS_v5_lHenze.pdf)

## X-Plat

* [pongoOS](https://github.com/checkra1n/pongoOS) ⭐ 2,739 | 🐛 50 | 🌐 C | 📅 2025-07-03
* [Android on pongoOS](https://github.com/corellium/projectsandcastle) ⭐ 2,099 | 🐛 10 | 🌐 C | 📅 2023-03-25
  * [iphonelinux](https://github.com/planetbeing/iphonelinux) ⭐ 619 | 🐛 14 | 🌐 C | 📅 2023-07-09
* [Corellium's M1 Branch](https://github.com/corellium/linux-m1) ⭐ 870 | 🐛 0 | 🌐 C | 📅 2021-02-24
* [Asahi Linux for M1](https://asahilinux.org)

## Safety / Protection

* [`mvt-project/mvt`](https://github.com/mvt-project/mvt) ⭐ 12,902 | 🐛 40 | 🌐 Python | 📅 2026-08-18
* [`rickmark/isafety`](https://github.com/rickmark/isafety) ⭐ 24 | 🐛 2 | 🌐 Python | 📅 2026-01-31
* [Mobile Verification Toolkit](https://docs.mvt.re/en/latest/)

## [CREDITS](CREDITS)

Hack Different - Apple Knowledge is a product of the entire community and belongs to the community.  It is
facilitated by the volunteer work of the Hack Different moderation team.

If you have issue with the design or workflow of this repository, blame me ([`rickmark`](https://github.com/rickmark))
as I setup and configured most of it.  (it me).  If you have feedback, join the `#apple-knowledge` channel of the
discord server.

Portions of data and knowledge come from
[TheiPhoneWiki](https://theiphonewiki.org), [libimobiledevice's website](https://libimobiledevice.org), and
[checkra1n's website](https://checkra.in), as well as the individuals who brought you those projects (and many more!)

Special mention to Jonathan Levin and Amit Singh for taking the time to publish books on these topics.

* [Mac OS Internals by Singh](https://www.amazon.com/Mac-OS-Internals-Approach-paperback/dp/0134426541)
* [Mac and iOS Internals by Levin](https://www.amazon.com/Mac-OS-iOS-Internals-Apples/dp/1118057651)
* [\*OS Internals - User Mode by Levin](https://www.amazon.com/dp/099105556X/ref=as_sl_pc_qf_sp_asin_til?tag=newosxbookcom-20\&linkCode=w00\&linkId=25d40cd80f346c76537ef5fb1ea1ed81\&creativeASIN=099105556X)
* [\*OS Internals - Kernel Mode by Levin](https://www.amazon.com/dp/0991055578/ref=as_sl_pc_tf_til?tag=newosxbookcom-20\&linkCode=w00\&linkId=1b6f861f86e509fd79773eb10adc0bbf\&creativeASIN=0991055578)
* [\*OS Internals - Security by Levin](https://www.amazon.com/dp/0991055535/ref=as_sl_pc_qf_sp_asin_til?tag=newosxbookcom-20\&linkCode=w00\&linkId=0b61c945365c9c37cd3cf88f10a5f629\&creativeASIN=0991055535)

A list of all projects and their contributors is at [CREDITS](CREDITS) and is updated by a script.  If there are
persons not updated due to limitations, please PR the CREDITS page and call them out.

### Setting up `overcommit`, the linters, and the build

Main article is in [BUILD](BUILD.md)

To keep the repo, docs, and data tidy, we use a tool called `overcommit` to connect up the git hooks to a
set of quality checks.  The fastest way to get setup is to run the following to make sure you have all the tools:

```shell
brew install hunspell
gem install overcommit bundler
bundle install
overcommit --install
```

### Why not \<insert wiki here>

Wiki's best serve prose, and part of the goal here is to leverage machine readable and ingestable information with
human augmentation wherever possible.

As of 2022, GitHub has 56 million users.  That means that there are 56 million people who are able to contribute
directly to this repo via a fork and PR, in opposition to wiki's which have a relatively small number of potential
editors.  The PR process also allows for modifications to be reviewed, commented and debated before inclusion.

## License

The contents of this repo are dual-licensed:

Code and data licensed under the [MIT](https://opensource.org/licenses/MIT) license

Documents also licensed under the CC-BY-SA

[![Creative Commons License](https://i.creativecommons.org/l/by-sa/4.0/88x31.png){style="border-width:0"}
](http://creativecommons.org/licenses/by-sa/4.0/){rel=license}
[Apple Knowledge](http://creativecommons.org/licenses/by-sa/4.0/){:xmlns:dct="<http://purl.org/dc/terms/>",
:property="dct:title"} by
[Hack Different](https://github.com/hack-different/apple-knowledge) ⭐ 1,370 | 🐛 4 | 🌐 Ruby | 📅 2026-08-16{:xmlns:cc="<http://creativecommons.org/ns#>",
:property="cc:attributionName", :rel="cc:attributionURL"}
is licensed under a \[Creative Commons Attribution-ShareAlike 4.0 International License]\(<http://creativecommons.org/>
licenses/by-sa/4.0/){:rel="license"}

## Dedication

> Here’s to the crazy ones, the misfits, the rebels, the troublemakers
>
> the round pegs in the square holes…
>
> the ones who see things differently — they’re not fond of rules…
>
> You can quote them, disagree with them, glorify or vilify them, but the only thing you can’t do is ignore them because
> they change things…
>
> They push the human race forward, and while some may see them as the crazy ones,
>
> we see genius,
>
> because the ones who are crazy enough to think that they can change the world,
>
> are the ones who do.
>
> — Steve Jobs, 1997

Also dedicated to the volunteer work of those who use this for good, and deny the shadow to those who seek to harm.

***

> _Enhansomed by [enhansome](https://github.com/enhansome) on 2026-08-18._
