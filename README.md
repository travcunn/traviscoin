TravisCoin Core integration/staging tree
=====================================


Current Exchanges and Previous Transactions in the wild:
----------------
| travcoin | value           |
|:--------:|-----------------|
| 1        | 1 tickle attack |
| 2        | 1 stick of gum  | 
| 20       | 1 box of kleenex|


What is TravisCoin?
----------------

TravisCoin is a currency accepted by Travis Cunningham to do any task for anyone, within reason. Payment tiers coming soon.

TravisCoin is an experimental new digital currency that enables instant payments to
anyone, anywhere in the world. TravisCoin uses a proof-of-stake method in order for
the TravisCoin blockchain network to achieve distributed consensus. TravisCoin Core is
the name of open source software which enables the use of this currency.

For more information, as well as an immediately useable, binary version of the
TravisCoin Core software, see https://github.com/travcunn/traviscoin

License
-------

TravisCoin Core is released under the terms of the MIT license. See [COPYING](COPYING) for more
information or see http://opensource.org/licenses/MIT.

Development process
-------------------

Developers work in their own trees, then submit pull requests when they think
their feature or bug fix is ready.

If it is a simple/trivial/non-controversial change, then one of the TravisCoin
development team members simply pulls it.

If it is a *more complicated or potentially controversial* change, then the patch
submitter will be asked to start a discussion (if they haven't already) on the
[Github Issue Tracker](https://github.com/travcunn/traviscoin/issues)

The patch will be accepted if there is broad consensus that it is a good thing.
Developers should expect to rework and resubmit patches if the code doesn't
match the project's coding conventions (see [doc/coding.md](doc/coding.md)) or are
controversial.

The `master` branch is regularly built and tested, but is not guaranteed to be
completely stable. [Tags](https://github.com/travcunn/traviscoin/tags) are created
regularly to indicate new official, stable release versions of TravisCoin.

Translations
------------

Changes to translations as well as new translations can be submitted to the
[Github Issue Tracker](https://github.com/travcunn/traviscoin/issues).

Translations are periodically pulled from Transifex and merged into the git repository. See the
[translation process](doc/translation_process.md) for details on how this works.

**Important**: We do not accept translation changes as GitHub pull requests because the next
pull from Transifex would automatically overwrite them again.
