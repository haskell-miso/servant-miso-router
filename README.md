🌐 servant-miso-router
============================

This package provides a client-side router that can be used with both [servant](https://hackage.haskell.org/packages/servant) and [miso](https://github.com/dmjio/miso) applications.

This package is an adaptation of [@ElvishJerricco](https://github.com/ElvishJerricco)'s [servant-router](https://github.com/ElvishJerricco/servant-router) package.

> [!Note]
> This package automatically re-exports the `HTML` combinator from [servant-miso-html](https://github.com/haskell-miso/servant-miso-html)

## Build

```shell
cabal build
```

```shell
nix develop --command bash -c 'cabal build'
```

# Develop

```shell
nix develop
```
