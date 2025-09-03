KittyCash Core
=============

Setup
---------------------
KittyCash Core is the original KittyCash client and it builds the backbone of the network. It downloads and, by default, stores the entire history of KittyCash transactions, which requires approximately 22 gigabytes of disk space. Depending on the speed of your computer and network connection, the synchronization process can take anywhere from a few hours to a day or more.

To download KittyCash Core, visit [kittycash.org](/).

Running
---------------------
The following are some helpful notes on how to run KittyCash Core on your native platform.

### Unix

Unpack the files into a directory and run:

- `bin/kittycash-qt` (GUI) or
- `bin/kittycashd` (headless)

### Windows

Unpack the files into a directory, and then run kittycash-qt.exe.

### macOS

Drag KittyCash Core to your applications folder, and then run KittyCash Core.

### Need Help?

* See the documentation at the [KittyCash Wiki](https://kittycash.info/) for help and more information.
* Ask for help on [#kittycash](https://webchat.freenode.net/#kittycash) on Freenode. If you don't have an IRC client, use [webchat here](https://webchat.freenode.net/#kittycash).
* Ask for help on the [KittyCashTalk](https://kittycashtalk.io/) forums, in the [Technical Support board](https://kittycashtalk.io/c/technical-support).

Building
---------------------
The following are developer notes on how to build KittyCash Core on your native platform. They are not complete guides, but include notes on the necessary libraries, compile flags, etc.

- [Dependencies](dependencies.md)
- [macOS Build Notes](build-osx.md)
- [Unix Build Notes](build-unix.md)
- [Windows Build Notes](build-windows.md)
- [FreeBSD Build Notes](build-freebsd.md)
- [OpenBSD Build Notes](build-openbsd.md)
- [NetBSD Build Notes](build-netbsd.md)
- [Gitian Building Guide (External Link)](https://github.com/bitcoin-core/docs/blob/master/gitian-building.md)

Development
---------------------
The KittyCash repo's [root README](/README.md) contains relevant information on the development process and automated testing.

- [Developer Notes](developer-notes.md)
- [Productivity Notes](productivity.md)
- [Release Notes](release-notes.md)
- [Release Process](release-process.md)
- [Source Code Documentation (External Link)](https://doxygen.bitcoincore.org/)
- [Translation Process](translation_process.md)
- [Translation Strings Policy](translation_strings_policy.md)
- [JSON-RPC Interface](JSON-RPC-interface.md)
- [Unauthenticated REST Interface](REST-interface.md)
- [Shared Libraries](shared-libraries.md)
- [BIPS](bips.md)
- [Dnsseed Policy](dnsseed-policy.md)
- [Benchmarking](benchmarking.md)

### Resources
* Discuss on the [KittyCashTalk](https://kittycashtalk.io/) forums.
* Discuss general KittyCash development on #kittycash-dev on Freenode. If you don't have an IRC client, use [webchat here](https://webchat.freenode.net/#kittycash-dev).

### Miscellaneous
- [Assets Attribution](assets-attribution.md)
- [bitcoin.conf Configuration File](bitcoin-conf.md)
- [Files](files.md)
- [Fuzz-testing](fuzzing.md)
- [Reduce Memory](reduce-memory.md)
- [Reduce Traffic](reduce-traffic.md)
- [Tor Support](tor.md)
- [Init Scripts (systemd/upstart/openrc)](init.md)
- [ZMQ](zmq.md)
- [PSBT support](psbt.md)

License
---------------------
Distributed under the [MIT software license](/COPYING).
