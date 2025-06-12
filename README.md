## Current work:

Motorola smartphones are starting to get [kernel protections](https://motorolanews.com/motorola-introduces-the-motorola-edge-40-business-edition/#:~:text=With%20moto%20edge%2040%20business%20edition%2C%20Motorola%20is,threats%20and%20exploits%20used%20to%20target%20their%20devices.), and many cutting-edge and fine grained protections are arriving in newer (2025) device models, conditioned on stability and performance constraints. Check out the draft schematics for the [seccomp filter purity test](https://lore.kernel.org/all/hkwtlwrpowebiwv4yifjsgjc5plg2cczp7wfzzuqhzi7lsj6lp@i753ef5xqnga/T/#m6f3dbc05266e98930e8c9abee62905b4e2cb58f9) and [PXNTable across vmalloc](https://lore.kernel.org/all/20240416122254.868007168-5-mbland@motorola.com/) for examples.

I am lucky to be able to acknowledge that there are still [hard problems](https://github.blog/author/mymo/) to be resolved for all Linux systems, and that there are awesome people working on them, see the [KSPP](https://github.com/KSPP)! There is a roundtable session on preventions for these recent exploits at the [2025 Linux Security Summit](https://events.linuxfoundation.org/linux-security-summit-north-america/).

## Other work:

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

