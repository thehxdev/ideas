# Project Ideas
When I have an idea, I note that here. There are some other places to find project idea:
- [Project-Based-Learning](https://github.com/practical-tutorials/project-based-learning)
- [Build-Your-Own-X](https://github.com/codecrafters-io/build-your-own-x)
- [Other project ideas repository list](https://www.reddit.com/r/learnprogramming/wiki/faq/#wiki_where_can_i_find_practice_exercises_and_project_ideas.3F)

---
## Suggestions for watching
- [The Myth of the Genius Programmer (Google I/O 2009)](https://youtu.be/0SARbwvhupQ?si=WLf15NisHCM9PoGT)
- [JSON parser 100% from scratch in Haskell](https://youtu.be/N9RUqGYuGfw?si=wMULIalYKDSAPXNy)
- [Reverse engineering the MOS 6502 CPU](https://youtu.be/fWqBmmPQP40?si=0A4DwRJrX33RGFoe)
- [Stop writing classes](https://youtu.be/o9pEzgHorH0?si=TMFT4l78z4AQ9vKV)
- [CppCon 2014: Mike Acton "Data-Oriented Design and C++"](https://youtu.be/rX0ItVEVjHc)
- [Practical Data-Oriented design](https://youtu.be/IroPQ150F6c)
- [Intro to Data-Oriented design](https://youtu.be/WwkuAqObplU?si=aAv7CiLUJ3B8QJBQ)
- [TGC 2017 - Mike Acton: Solving the right problems for the engine programmers](https://youtu.be/4B00hV3wmMY)
- [GOTO 2024 - Java, How fast can you parse 1 Bilion rows of weather data?](https://youtu.be/EFXxXFHpS0M?si=HqwWbHIBPqK9IUfr)
- [C++ on Sea 2023 - \*(char\*)0=0;](https://youtu.be/dFIqNZ8VbRY?si=gPtE6T_qQU1e6i7r)
- [How Linux kernel handles a TCP connection](https://youtu.be/ck4WvYM9V4c?si=gm-VB0VRuZGkp-tV)
- [Clean code, Horrible performance](https://youtu.be/tD5NrevFtbU?si=wDdtm3i1u7k-J-H_)
- [GOD MODE UNLOCKED - Hardware Backdoors in x86 CPU](https://youtu.be/_eSAF_qT_FY?si=vYwpI3O8nMQ4CYLO)
- [How to Learn and Study](https://youtu.be/ddq8JIMhz7c?si=_X87AVVDwnGsdSWP)
- [How to be a git expert](https://youtu.be/hZS96dwKvt0?si=Q_Vjj4VHYQquos7X)

## Suggestions for reading
- [The best engineering interview question I’ve ever gotten](https://quuxplusone.github.io/blog/2022/01/06/memcached-interview/)
- [Teach yourself CS](https://teachyourselfcs.com/)
- [Putting the “You” in CPU](https://cpu.land/)
- [Data alignment: Straighten up and fly right](https://developer.ibm.com/articles/pa-dalign/)
- [Compiling C to WebAssembly without Emscripten](https://surma.dev/things/c-to-webassembly/)
- [How Wine works 101](https://werat.dev/blog/how-wine-works-101/)
- [The Definitive Guide to Linux System Calls](https://blog.packagecloud.io/the-definitive-guide-to-linux-system-calls/)
- [The Illustrated TLS 1.3 Connection](https://tls13.xargs.org/)
- [SHA256 algorithm explained](https://sha256algorithm.com/)
- [Less Known C](https://jorenar.com/blog/less-known-c)
- [The curse of strong typing](https://fasterthanli.me/articles/the-curse-of-strong-typing)
---

## Networking
- Guessing number through TCP (clients connect with `nc` or `telnet`)
- `.torrent` file parser
- Magnet link parser
- Bittorrent client
- Torrent tracker server
- P2P TCP chat server
- IRC server/client
  - [IRCv3 Specs](https://ircv3.net/irc/)
  - [IRCv3 Implementation in Golang](https://github.com/ergochat/ergo)
- netcat/telnet clone
- HTTP web framework
- File server
- Distributed file storage
- Concurrent In-memory Key/Value store or cache (in form of a library or dedicated program like redis/memcached)
- SNI Proxy
  - [Writing a SNI proxy in 115 lines of Go](https://www.agwa.name/blog/post/writing_an_sni_proxy_in_go)
- DNS/DoH server
- DoH client
- Simple blockchain
- Load balancer
- Websocket library
  - [RFC 6455](https://datatracker.ietf.org/doc/html/rfc6455)
- A file downloder with multi-part downloads
- Concurrent webserver
- Echo server
- Simple pastebin backend service

## Emulator / Virtual Machine
- Chip-8 emulator
  - [How to write chip-8 emulator](https://multigesture.net/articles/how-to-write-an-emulator-chip-8-interpreter/)
  - [Chip-8 technical reference](http://devernay.free.fr/hacks/chip8/C8TECH10.HTM)
- Z80 emulator
- [lc3-vm / Write your own virtual machine](https://www.jmeiners.com/lc3-vm/)

## Compiler / Interpreter
- [Crafting Interpreters](https://craftinginterpreters.com/)
- C compiler
- Lisp interpreter
  - [Build your own Lisp](https://www.buildyourownlisp.com)
  - [Make a Lisp](https://github.com/kanaka/mal)
- Assembler
- Linker
- Parser combinator
- Brainfuck interpreter or JIT compiler
  - [I made JIT Compiler for Brainf\*ck lol (Youtube)](https://youtu.be/mbFY3Rwv7XM)
  - [bfjit](https://github.com/tsoding/bfjit)
  - Try to optimize you interpreter as much as you can :)
- Simple JVM/Python bytecode interpreter
- LLVM stuff :)
- A build system in a single header C file
  - [nob.h](https://github.com/tsoding/nob.h)

## Low level programming
- Simple x86/arm debugger
- Bootloader
- Simple operating system
- Memory allocation tracer (something like valgrind)
- Process open file tracer
- Arena memory allocator
- Garbage collector for C
- Simple Shell
- Linux kernel driver

## Misc
- GNU coreutils clone
- Concurrency library (like pthreads or a wrapper for pthreads)
- Golang channels in other languages
  - [Pure C89 implementation of Golang channels](https://github.com/rochus-keller/CspChan)
- Markdown to HTML
  - Extended: Blog writing page that user can Write normal Markdown with all links and images, then the server parses that, converts it to HTML, 
  downloads every downloadable url (like images), puts all files to a directory that belongs to that blog page ID.
- JSON/YAML/TOML/XML/CSV parser
- A package manager for Github releases
- Program to hide and obfuscate files
- Simple text editor (TUI or GUI)
