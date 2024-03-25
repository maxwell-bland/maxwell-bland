Motorola smartphones are starting to get [state-of-the-art kernel protections](https://motorolanews.com/motorola-introduces-the-motorola-edge-40-business-edition/#:~:text=With%20moto%20edge%2040%20business%20edition%2C%20Motorola%20is,threats%20and%20exploits%20used%20to%20target%20their%20devices.), brushing the dust off of a 14 year gap in work dedicated to hypervisor-level kernel protections.

[PDF redactions are broken](https://arxiv.org/abs/2206.02285), 
even the nontrivial ones where the underlying text is removed.
[Large parts of the tool are now available!](https://github.com/maxwell-bland/deredaction)

[Y-AFL](https://github.com/maxwell-bland/yafl) is the architecture-independent 
system-mode QEMU fuzzer used in Jetset to build an exploit for the Communication 
Management Unit of a Boeing 737.
The important discovery is that CRIU is an excellent method for quickly creating effective fuzzers for complex software systems.

[Jetset](https://github.com/aerosec/jetset) is a symbolic executor which uses
QEMU's TCG IR during analysis, allowing for the incorporation of hardware
semantics into program analysis routines.

[G2](https://github.com/BillHallahan/G2) is a symbolic executor for Haskell,
allowing for advanced bug detection and constraint solving in the context of
lazy, functional languages.

[Bluetana](https://www.usenix.org/system/files/sec19-bhaskar.pdf) is an Android application 
and data analysis framework for detecting credit card skimming devices using bluetooth. The useful Android (Java) snippets, sanitized of anything sensitive, 
are available [here](https://github.com/maxwell-bland/android-snippets).

