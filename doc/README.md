Quaz Core 0.12.1
=====================

This is the official reference wallet for Quaz digital currency and comprises the backbone of the Quaz peer-to-peer network. You can [download Quaz Core](https://www.quaz.org/downloads/) or [build it yourself](#building) using the guides below.

Running
---------------------
The following are some helpful notes on how to run Quaz on your native platform.

### Unix

Unpack the files into a directory and run:

- `bin/quaz-qt` (GUI) or
- `bin/quazd` (headless)

### Windows

Unpack the files into a directory, and then run quaz-qt.exe.

### OS X

Drag Quaz-Qt to your applications folder, and then run Quaz-Qt.

### Need Help?

* See the [Quaz documentation](https://quazpay.atlassian.net/wiki/display/DOC)
for help and more information.
* Ask for help on [#quazpay](http://webchat.freenode.net?channels=quazpay) on Freenode. If you don't have an IRC client use [webchat here](http://webchat.freenode.net?channels=quazpay).
* Ask for help on the [QuazTalk](https://quaztalk.org/) forums.

Building
---------------------
The following are developer notes on how to build Quaz Core on your native platform. They are not complete guides, but include notes on the necessary libraries, compile flags, etc.

- [OS X Build Notes](build-osx.md)
- [Unix Build Notes](build-unix.md)
- [Windows Build Notes](build-windows.md)
- [OpenBSD Build Notes](build-openbsd.md)
- [Gitian Building Guide](gitian-building.md)

Development
---------------------
The Quaz Core repo's [root README](/README.md) contains relevant information on the development process and automated testing.

- [Developer Notes](developer-notes.md)
- [Multiwallet Qt Development](multiwallet-qt.md)
- [Release Notes](release-notes.md)
- [Release Process](release-process.md)
- Source Code Documentation ***TODO***
- [Translation Process](translation_process.md)
- [Translation Strings Policy](translation_strings_policy.md)
- [Unit Tests](unit-tests.md)
- [Unauthenticated REST Interface](REST-interface.md)
- [Shared Libraries](shared-libraries.md)
- [BIPS](bips.md)
- [Dnsseed Policy](dnsseed-policy.md)

### Resources
* Discuss on the [QuazTalk](https://quaztalk.org/) forums, in the Development & Technical Discussion board.
* Discuss on [#quazpay](http://webchat.freenode.net/?channels=quazpay) on Freenode. If you don't have an IRC client use [webchat here](http://webchat.freenode.net/?channels=quazpay).

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
