# OpenOSX

**Status:** ➤ *Initial fork of Apple's XNU kernel repository*

OpenOSX is the first step toward a fully open-source, macOS-compatible operating system. At present, this repository is a direct fork of Apple’s XNU kernel sources. Our goal is to assemble Darwin components into a community-driven project, but we need collaborators to drive development in these key areas for now:

1. Help analyze, document, and modify the XNU codebase.

2. Design reproducible build scripts (Docker/CI) for macOS and Linux.

3. Identify and integrate Darwin user-space packages.

4. Configure EFI stubs and test with QEMU.

5. Verify compatibility of included components under APSL 2.0 and BSD-style licenses.

6. Debugging the Codebase and proposing bugfixes.

## Table of Contents

* [About This Fork](#about-this-fork)
* [Want to Contribute?](#call-for-contributors)
* [How to Get Involved](#how-to-get-involved)
* [License](#license)

## About This Fork

This repository has been forked directly from Apple’s open-source XNU kernel release. No changes have been made yet. We intend to:

1. Make a MacOS compatible Operating-System with a GUI.
2. Create a reproducible build environment.
3. Develop documentation and roadmaps for kernel and userland work.

## Want to Contribute?

We welcome anyone interested in operating systems, kernel development, or open-source governance. Whether you are a seasoned kernel hacker or new to systems work, your contribution matters:

* Open issues to propose improvements or identify pain points.
* Share build logs and environment notes.
* Draft RFCs for feature enhancements.
* Join discussions on architectural decisions.

## How to Get Involved

1. Fork this repository and clone locally.
2. Report any build errors or setup issues via GitHub Issues.
3. Propose scripts or configurations by opening pull requests.

Use GitHub Discussions to introduce yourself, propose ideas, or ask for help: [https://github.com/LibreCorp/OpenOSX/discussions](https://github.com/LibreCorp/OpenOSX/discussions)

## License

All content in this repository is under the Apple Public Source License v2.0 (APSL) as from the original XNU repository. See [APPLE_LICENSE](APPLE_LICENSE) for details.
