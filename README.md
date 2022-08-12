# wallet3

This repository contains info and discussions about a **so-far hypothetical** full core wallet rewrite from scratch to implement Seraphis and Jamtis support in the Monero codebase, a project with a "working title" of *wallet3*.

The code would use @UkoeHB's Seraphis function library that is [here](https://github.com/UkoeHB/monero/tree/seraphis_lib/src/seraphis). (See also the [resources](https://github.com/seraphis-migration/strategy/wiki/Seraphis-and-Jamtis-Resources) page in the strategy wiki.) Whether and how it would also internally use the existing `wallet2` is unclear so far.

There is a principal wallet migration strategy described in the strategy wiki [here](https://github.com/seraphis-migration/strategy/wiki/Principal-Wallet-Migration-Strategies) that is also called *wallet3*. What is described here differs from that because the starting point is quite different: The *seraphis_wallet code from UkoeHB* that the strategy is built on did not come to be as originally expected, but an extensive Seraphis function library that should contain all the building blocks needed for building a wallet proper.

The issues in this repository describe important issues that would play a role in such a full wallet rewrite, which as already mentioned may or may **not** happen.
