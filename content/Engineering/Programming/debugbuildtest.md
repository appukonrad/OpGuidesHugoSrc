# Chapter 16 - Debugging, Automated Building and Testing

## Automated Building

## Debugging

[./missing-semester - Debugging and Profiling](https://missing.csail.mit.edu/2020/debugging-profiling/)

### Software Debugging

[TODO]

GDB with Gef, interpreted languages, embedded systems, non-code issues (boot problems, glitchy behavior), hardware failures, valgrind, various trace programs, print debugging extended

### Debuggers

[GDB Frontend](https://github.com/rohanrhu/gdb-frontend)

[GDB + GEF](https://gef.readthedocs.io/en/master/)

[The State of Linux Debuggers (Jamie Brandon's Blog)](https://scattered-thoughts.net/writing/the-state-of-linux-debuggers/) ← This is a decent rant about why most debuggers sort of suck. And yeah, they do. But we still sorta need them

[Advanced GDB Usage (Interrupt)](https://interrupt.memfault.com/blog/advanced-gdb)

https://rr-project.org

\+ valgrid in here somewhere, ref 11- low level prog

#### Static Analysis

[CodeChecker using LLVM/Clang (GitHub)](https://github.com/Ericsson/codechecker)

### Hardware Debugging

common interfaces, simulation, serial/print debugging (slow), internal data logging, physical indicators of internal state, hardware to facilitate debugging (LED 'byte')

[TODO] [Embedded C/C++ Unit Testing Basics (Interrupt)](https://interrupt.memfault.com/blog/unit-testing-basics)

[TODO] [Faster Debugging with Watchpoints (Interrupt)](https://interrupt.memfault.com/blog/cortex-m-watchpoints)

## Testing

```
@jnesselr replying to @alicegoldfuss (Nov 13, 2018)
+----------------------------------------------------+
|Me: *does major refactor*                           |
|Tests: ✓                                            |
|Me: I don't believe you                             |
+----------------------------------------------------+
[Suspended User]
+----------------------------------------------------+
|Me: *deliberately breaks something, just to be sure*|
|Tests: ✓                                            |
|Me: oh no                                           |
+----------------------------------------------------+
@boo_radley
+----------------------------------------------------+
|Me: *changes nothing*                               |
|Tests: ✗                                            |
|Me: oh no                                           |
+----------------------------------------------------+
[Suspended User]
+----------------------------------------------------+
|Me: *runs tests again*                              |
|Tests: ✔                                            |
|Me: oh no no no                                     |
+----------------------------------------------------+
src: https://twitter.com/boo_radley/status/1062513898954391552
```

### Software Testing

unit tests, integration tests, performance testing - https://github.com/sharkdp/hyperfine

### Hardware Testing

## Automated Building and Testing

[TODO]

Fuzzing (sandsifter), make and alts, etc.

## Continuous Integration

## Continuous Deployment

## Benchmarking

https://github.com/sharkdp/hyperfine

