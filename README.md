[PDF redactions are broken](https://arxiv.org/abs/2206.02285), 
even the nontrivial ones where the underlying text is removed. I made ~1,500 commits!
The tool is not released, but one public result is a highly precise 
[PDF text analysis library](https://github.com/maxwell-bland/glyph-positioning). [Defenses](https://github.com/maxwell-bland/redaction-defenses).

[Y-AFL](https://github.com/maxwell-bland/yafl) is the architecture-independent 
system-mode QEMU fuzzer used in Jetset to build an exploit for the Communication 
Management Unit of a Boeing 737.
I wrote the fuzzer from scratch with some guidance from Triforce AFL's ideas. 
The important discovery is that CRIU is an excellent method for quickly creating effective fuzzers for complex software systems.

[Jetset](https://github.com/aerosec/jetset) is a symbolic executor which uses
QEMU's TCG IR during analysis, allowing for the incorporation of hardware
semantics into program analysis routines.
Evan, Yifei, and Myself all contributed equally to the executor.

[G2](https://github.com/BillHallahan/G2) is a symbolic executor for Haskell,
allowing for advanced bug detection and constraint solving in the context of
lazy, functional languages.
Bill and Anton did most to all of this. I wrote some verification routines in Haskell, Python, and Scheme.

[Bluetana](https://www.usenix.org/system/files/sec19-bhaskar.pdf) is an Android application 
and data analysis framework for detecting credit card skimming devices using bluetooth.
I made ~1,000 commits! The useful Android (Java) snippets, sanitized of anything sensitive, 
are available [here](https://github.com/maxwell-bland/android-snippets).

