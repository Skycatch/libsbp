# [SBP Bindings for Haskell][1]

Haskell client for Swift Binary Protocol (SBP).

## Requirements

`haskell-stack`: [Instructions here](https://github.com/commercialhaskell/stack/blob/master/doc/install_and_upgrade.md).

## Install from Hackage

Available on [Hackage as `sbp`](http://hackage.haskell.org/package/sbp).

To install from Hackage using `stack`:

    $ stack install --resolver lts-6.25 sbp
    
Note that we explicitly specify the `lts-6.25` resolver, `libsbp` may fail to build with more recent resolvers.

## Setup

To build:

    $ stack build

To install:

    $ stack install

To test and benchmark:

    $ stack test && stack bench

To deploy to Hackage:

    $ stack upload

## Usage Examples (TODO)

## References

# LICENSE

Copyright © 2015 Swift Navigation Inc.

[1]: https://github.com/swift-nav/libsbp/tree/master/haskell
