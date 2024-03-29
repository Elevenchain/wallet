elevenchain Core staging tree 18.0
===========================

|CI|master|develop|
|-|-|-|
|Gitlab|[![Build Status](https://gitlab.com/elevenchainpay/elevenchain/badges/master/pipeline.svg)](https://gitlab.com/elevenchainpay/elevenchain/-/tree/master)|[![Build Status](https://gitlab.com/elevenchainpay/elevenchain/badges/develop/pipeline.svg)](https://gitlab.com/elevenchainpay/elevenchain/-/tree/develop)|

https://www.elevenchain.com

For an immediately usable, binary version of the elevenchain Core software, see
https://github.com/Elevenchain/wallet/releases/tag/V1.1

Further information about elevenchain Core is available in the [doc folder](/doc).

What is elevenchain?
-------------

ElevenChain was born out of our dissatisfaction with existing cryptocurrencies. We found that many cryptocurrencies suffer from issues such as slow transaction speeds, network congestion, and high energy consumption. Therefore, we decided to develop a new type of cryptocurrency to address these problems.


Technical Features
-------------
ElevenChain adopts the X11 algorithm, an advanced algorithm introduced by Dash. The X11 algorithm enhances block generation security by combining multiple hash functions while reducing mining energy consumption. This makes ElevenChain an environmentally friendly and efficient cryptocurrency.





License
-------

elevenchain Core is released under the terms of the MIT license. See [COPYING](COPYING) for more
information or see https://opensource.org/licenses/MIT.

Development Process
-------------------

The `master` branch is meant to be stable. Development is normally done in separate branches.
[Tags](https://github.com/Elevenchain/tags) are created to indicate new official,
stable release versions of elevenchain Core.

The contribution workflow is described in [CONTRIBUTING.md](CONTRIBUTING.md)
and useful hints for developers can be found in [doc/developer-notes.md](doc/developer-notes.md).

Testing
-------

Testing and code review is the bottleneck for development; we get more pull
requests than we can review and test on short notice. Please be patient and help out by testing
other people's pull requests, and remember this is a security-critical project where any mistake might cost people
lots of money.

### Automated Testing

Developers are strongly encouraged to write [unit tests](src/test/README.md) for new code, and to
submit new unit tests for old code. Unit tests can be compiled and run
(assuming they weren't disabled in configure) with: `make check`. Further details on running
and extending unit tests can be found in [/src/test/README.md](/src/test/README.md).

There are also [regression and integration tests](/test), written
in Python.
These tests can be run (if the [test dependencies](/test) are installed) with: `test/functional/test_runner.py`

The Travis CI system makes sure that every pull request is built for Windows, Linux, and macOS, and that unit/sanity tests are run automatically.

### Manual Quality Assurance (QA) Testing

Changes should be tested by somebody other than the developer who wrote the
code. This is especially important for large or high-risk changes. It is useful
to add a test plan to the pull request description if testing the changes is
not straightforward.

Translations
------------

Changes to translations as well as new translations can be submitted to
[elevenchain Core's Transifex page](https://www.transifex.com/projects/p/elevenchain/).

Translations are periodically pulled from Transifex and merged into the git repository. See the
[translation process](doc/translation_process.md) for details on how this works.

**Important**: We do not accept translation changes as GitHub pull requests because the next
pull from Transifex would automatically overwrite them again.
