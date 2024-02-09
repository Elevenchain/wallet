elevenchain Core
==========

This is the official reference wallet for elevenchain digital currency and comprises the backbone of the elevenchain peer-to-peer network. You can [download elevenchain Core](https://www.elevenchain.org/downloads/) or [build it yourself](#building) using the guides below.

Running
---------------------
The following are some helpful notes on how to run elevenchain Core on your native platform.

### Unix

Unpack the files into a directory and run:

- `bin/elevenchain-qt` (GUI) or
- `bin/elevenchaind` (headless)

### Windows

Unpack the files into a directory, and then run elevenchain-qt.exe.

### macOS

Drag elevenchain Core to your applications folder, and then run elevenchain Core.

### Need Help?

* See the [elevenchain documentation](https://docs.elevenchain.org)
for help and more information.
* Ask for help on [elevenchain Discord](http://stayelevenchainy.com)
* Ask for help on the [elevenchain Forum](https://elevenchain.com/forum)

Building
---------------------
The following are developer notes on how to build elevenchain Core on your native platform. They are not complete guides, but include notes on the necessary libraries, compile flags, etc.

- [Dependencies](dependencies.md)
- [macOS Build Notes](build-osx.md)
- [Unix Build Notes](build-unix.md)
- [Windows Build Notes](build-windows.md)
- [OpenBSD Build Notes](build-openbsd.md)
- [NetBSD Build Notes](build-netbsd.md)
- [Gitian Building Guide](gitian-building.md)

Development
---------------------
The elevenchain Core repo's [root README](/README.md) contains relevant information on the development process and automated testing.

- [Developer Notes](developer-notes.md)
- [Productivity Notes](productivity.md)
- [Release Notes](release-notes.md)
- [Release Process](release-process.md)
- Source Code Documentation ***TODO***
- [Translation Process](translation_process.md)
- [Translation Strings Policy](translation_strings_policy.md)
- [JSON-RPC Interface](JSON-RPC-interface.md)
- [Unauthenticated REST Interface](REST-interface.md)
- [Shared Libraries](shared-libraries.md)
- [BIPS](bips.md)
- [Dnsseed Policy](dnsseed-policy.md)
- [Benchmarking](benchmarking.md)

### Resources
* See the [elevenchain Developer Documentation](https://elevenchain.readme.io/)
  for technical specifications and implementation details.
* Discuss on the [elevenchain Forum](https://elevenchain.com/forum), in the Development & Technical Discussion board.
* Discuss on [elevenchain Discord](http://stayelevenchainy.com)
* Discuss on [elevenchain Developers Discord](http://chat.elevenchaindevs.org/)

### Miscellaneous
- [Assets Attribution](assets-attribution.md)
- [elevenchain.conf Configuration File](elevenchain-conf.md)
- [Files](files.md)
- [Fuzz-testing](fuzzing.md)
- [I2P Support](i2p.md)
- [Init Scripts (systemd/upstart/openrc)](init.md)
- [PSBT support](psbt.md)
- [Reduce Memory](reduce-memory.md)
- [Reduce Traffic](reduce-traffic.md)
- [Tor Support](tor.md)
- [ZMQ](zmq.md)

License
---------------------
Distributed under the [MIT software license](/COPYING).
