# Pandacoin logo![pandacoin](https://user-images.githubusercontent.com/83800886/117408444-893b4f80-af42-11eb-8ce4-192c8c707403.jpg)

# Pandacoin Core  
pandacoin is a cryptocurrency like Bitcoin, Out of the protection of the environment and Energy will be used (Pos) principle of work for mining。
Panda open payment system is a virtual currency network, the future of electronic payment platform. Its goal is to build a decentralized virtual currency system that allows anyone to create their own currency.

## License – Much license ⚖️
pandacoin Core is released under the terms of the MIT license. See
[COPYING](COPYING) for more information or see
[opensource.org](https://opensource.org/licenses/MIT)

## Development and contributions – omg developers
Development is ongoing, and the development team, as well as other volunteers,
can freely work in their own trees and submit pull requests when features or
bug fixes are ready.

#### Version strategy
Version numbers are following ```major.minor.patch``` semantics.

#### Branches
There are 3 types of branches in this repository:

- **master:** Stable, contains the latest version of the latest *major.minor* release.
- **maintenance:** Stable, contains the latest version of previous releases, which are still under active maintenance. Format: ```<version>-maint```
- **development:** Unstable, contains new code for planned releases. Format: ```<version>-dev```

*Master and maintenance branches are exclusively mutable by release. Planned*
*releases will always have a development branch and pull requests should be*
*submitted against those. Maintenance branches are there for **bug fixes only,***
*please submit new features against the development branch with the highest version.*

#### Contributions ✍️

Developers are strongly encouraged to write [unit tests](src/test/README.md) for new code, and to
submit new unit tests for old code. Unit tests can be compiled and run
(assuming they weren't disabled in configure) with: `make check`. Further details on running
and extending unit tests can be found in [/src/test/README.md](/src/test/README.md).

There are also [regression and integration tests](/qa) of the RPC interface, written
in Python, that are run automatically on the build server.
These tests can be run (if the [test dependencies](/qa) are installed) with: `qa/pull-tester/rpc-tests.py`

Changes should be tested by somebody other than the developer who wrote the
code. This is especially important for large or high-risk changes. It is useful
to add a test plan to the pull request description if testing the changes is
not straightforward.

## Very Much Frequently Asked Questions ❓

### How much panda can exist? 
Early 2021 (approximately a year and a half after release) there will be
approximately 2100,000,000,000 coins.
Each subsequent block will grant 10,00 coins to encourage miners to continue to
secure the network and make up for lost wallets on hard drives/phones/lost
encryption passwords/etc.


## Development tips and tricks

**compiling for debugging**

Run `configure` with the `--enable-debug` option, then `make`. Or run `configure` with
`CXXFLAGS="-g -ggdb -O0"` or whatever debug flags you need.

How to get pandacoin? 

Early on the project will rely on trc20 to issue tokens and fly 100 pandacoins to each encrypted user of the whole network, and open the transaction until the mapping to the main network.

The characteristics of the panda
1. Zero transaction costs
Transaction between different fiat currencies is usually charged a few percent plus a transaction fee. Any transaction fee for Panda is zero.
2, anonymous
Panda Network does not require users to provide email, name, or any other information to provide privacy for consumers.
3, safety
Sending panda is just like sending cash. After receiving it, there is no other charge. The payer must provide personal information by credit card and check, which may lead to fraud.
4, reliable,
Since Panda transactions are not reversible, merchants can trade with anyone without fear of resigning.
5. Anyone can run PANDA
