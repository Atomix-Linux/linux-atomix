# Linux kernel based on ArchLinux and patched for Atomix Linux (forked from linux-chimeraos under GPL 2.0 License)

We aim to provide early access to some upstream patches and some compatibility
fixes we discover and test. Yet we try to provide a stable experience.

This repository will use a PKGBUILD to build ArchLinux packages and publish
them as GitHub releases in binary package form. We currently do not provide a
custom ArchLinux repository.

# Contributing

Feel free to submit Pull Requests if a patch has merit over the current stable
linux package. Take a look at our discord server to be part of the discussion
around it

# Patch locations
We have two types of patches. Patches that are stabilized will be merged our [linux repo](https://github.com/Atomix-Linux/linux). There a branch is kept for each version.
Those patches are part of the -chos* patch set. Furthermore we have experiments which are located in the patch file. This is one experiment at the time. Changes in this will result in a new pkgrel version.
