Ascension Core 0.13.2
=====================

Setup
---------------------
[Ascension Core](http://ascension.org/en/download) is the original Ascension client and it builds the backbone of the network. However, it downloads and stores the entire history of Ascension transactions (which is currently several GBs); depending on the speed of your computer and network connection, the synchronization process can take anywhere from a few hours to a day or more.

Running
---------------------
The following are some helpful notes on how to run Ascension on your native platform.

### Unix

Unpack the files into a directory and run:

- `bin/ascension-qt` (GUI) or
- `bin/ascensiond` (headless)

### Windows

Unpack the files into a directory, and then run ascension-qt.exe.

### OS X

Drag Ascension-Core to your applications folder, and then run Ascension-Core.

### Need Help?

* See the documentation at the [Ascension Wiki](https://ascension.info/)
for help and more information.
* Ask for help on [#ascension](http://webchat.freenode.net?channels=ascension) on Freenode. If you don't have an IRC client use [webchat here](http://webchat.freenode.net?channels=ascension).
* Ask for help on the [AscensionTalk](https://ascensiontalk.io/) forums.

Building
---------------------
The following are developer notes on how to build Ascension on your native platform. They are not complete guides, but include notes on the necessary libraries, compile flags, etc.

- [OS X Build Notes](build-osx.md)
- [Unix Build Notes](build-unix.md)
- [Windows Build Notes](build-windows.md)
- [OpenBSD Build Notes](build-openbsd.md)
- [Gitian Building Guide](gitian-building.md)

Development
---------------------
The Ascension repo's [root README](/README.md) contains relevant information on the development process and automated testing.

- [Developer Notes](developer-notes.md)
- [Multiwallet Qt Development](multiwallet-qt.md)
- [Release Notes](release-notes.md)
- [Release Process](release-process.md)
- [Source Code Documentation (External Link)](https://dev.visucore.com/bitcoin/doxygen/)
- [Translation Process](translation_process.md)
- [Translation Strings Policy](translation_strings_policy.md)
- [Unit Tests](unit-tests.md)
- [Unauthenticated REST Interface](REST-interface.md)
- [Shared Libraries](shared-libraries.md)
- [BIPS](bips.md)
- [Dnsseed Policy](dnsseed-policy.md)
- [Benchmarking](benchmarking.md)

### Resources
* Discuss on the [AscensionTalk](https://ascensiontalk.io/) forums.
* Discuss project-specific development on #ascension on Freenode. If you don't have an IRC client use [webchat here](http://webchat.freenode.net/?channels=ascension).

### Miscellaneous
- [Assets Attribution](assets-attribution.md)
- [Files](files.md)
- [Tor Support](tor.md)
- [Init Scripts (systemd/upstart/openrc)](init.md)

License
---------------------
Distributed under the [MIT software license](http://www.opensource.org/licenses/mit-license.php).
This product includes software developed by the OpenSSL Project for use in the [OpenSSL Toolkit](https://www.openssl.org/). This product includes
cryptographic software written by Eric Young ([eay@cryptsoft.com](mailto:eay@cryptsoft.com)), and UPnP software written by Thomas Bernard.
