# proton-ge-custom-znver1
[Proton-ge-custom](https://github.com/GloriousEggroll/proton-ge-custom) builds optimized for znver1

After spending several hours trying to get podman to work in an ebuild, I decided it would be easier to just build on github actions.

# What does this do
This repository just contains a modified version of the github actions script availaible from the [proton-ge-custom](https://github.com/GloriousEggroll/proton-ge-custom) repo with a few modifications to run in a matrix and to patch the flags.

Currently only the `OPTIMIZE_FLAGS` are patched in the `Makefile.in` for now

# Disclaimer
I am not associated with the official [proton-ge-custom](https://github.com/GloriousEggroll/proton-ge-custom) so any problems with these builds, try first with the [official builds](https://github.com/GloriousEggroll/proton-ge-custom/releases) before reporting an issue over there, and if it is a problem with this build please feel free to open an issue here.
