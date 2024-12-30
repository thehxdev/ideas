# Project Ideas
When I have an idea, I note that here. There are some other places to find project idea:
- [Project-Based-Learning](https://github.com/practical-tutorials/project-based-learning)
- [Build-Your-Own-X](https://github.com/codecrafters-io/build-your-own-x)
- [Other project ideas repository list](https://www.reddit.com/r/learnprogramming/wiki/faq/#wiki_where_can_i_find_practice_exercises_and_project_ideas.3F)

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
