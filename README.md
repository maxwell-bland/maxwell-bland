Now that my Ph.D. work is done, my main WIP is rolling out production-ready, [state-of-the-art kernel protections](https://motorolanews.com/motorola-introduces-the-motorola-edge-40-business-edition/#:~:text=With%20moto%20edge%2040%20business%20edition%2C%20Motorola%20is,threats%20and%20exploits%20used%20to%20target%20their%20devices.)
to Motorola smartphones, improving on 14+ years of work dedicated to hypervisor-level kernel protections, and hacking
in preventions for scarcely discussed vulnerabilities introduced by the current Android GKI and Linux.

[PDF redactions are broken](https://arxiv.org/abs/2206.02285), 
even the nontrivial ones where the underlying text is removed. I made ~1,500 commits!
[Large parts of the tool are now available!](https://github.com/maxwell-bland/deredaction)

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

