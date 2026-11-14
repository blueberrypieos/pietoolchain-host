<!-- SPDX-License-Identifier: BSD-2-Clause -->
<!-- Copyright (c) 2026 The Blueberry Pie OS Authors -->
# pietoolchain-host

Host tools for building PIE. Includes cctools, the linker, mig, compiler
wrappers and shared build helpers.

Initialise the submodules with `git submodule update --init --recursive`.
Build a source package with `pie-source source`, extract it with
`dpkg-source -x`, then run `dpkg-buildpackage -b -us -uc` in the extracted tree.

The tools install under `/usr/lib/pietoolchain/toolchain`.
The shared helpers install under `/usr/share/pietoolchain`.
The `pietoolchain` transitional package installs these tools and the SDK.
