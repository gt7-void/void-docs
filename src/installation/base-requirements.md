# Base System Requirements

Void can be installed on very minimalist hardware, though we recommend the
following minimums for most installations:

| Architecture | CPU              | RAM  | Storage |
|--------------|------------------|------|---------|
| x86_64-glibc | x86_64           | 96MB | 700MB   |
| x86_64-musl  | x86_64           | 96MB | 600MB   |
| i686-glibc   | Pentium 4 (SSE2) | 96MB | 700MB   |

> Note: Flavor installations require more resources. How much more depends on
> the flavor.

Void is not available for i386, i486, or i586 architectures.

Before installing musl Void, please read [the "musl" section](./musl.md) of this
Handbook, so that you are aware of software incompatibilities.

It is highly recommended to have a network connection available during install
to download updates, but this is not required. ISO images contain installation
data on-disc and can be installed without network connectivity.
