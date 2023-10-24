# sdk-seven — Modern GBA SDK

sdk-seven provides all the necessary components for building software for the
Game Boy Advance. It is built from scratch with an emphasis on correctness and
performance. While still in active development, the core components have proven
quite solid already.

It includes the following components:

- libseven, a development library for interacting with the GBA hardware
- libutil, a small library of utility functions
- rt, a runtime library for building and running GBA ROMs
- Python helper scripts

Consider using [agbabi](https://github.com/felixjones/agbabi) for those.

[meson-gba](https://github.com/LunarLambda/meson-gba) makes it easy to use
sdk-seven and any number of additional libraries and tools.

[gba-toolchain](https://github.com/felixjones/gba-toolchain) provides similar
functionality, using CMake.

## Support

Development of sdk-seven and other GBA homebrew projects can be supported
through [Patreon](https://patreon.com/LunarLambda).

You can also reach out to us in the `#sdk-seven` channel in the
[gbadev Discord](https://discord.io/gbadev).
