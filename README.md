# LogicOcean Homebrew Tap

Homebrew formulae for [pgokf](https://github.com/LogicOcean/pgokf), a PostgreSQL
extension that turns Open Knowledge Format bundles into a queryable catalog.

## Install

```sh
brew tap logicocean/pgokf
brew install pgokf
```

The formula builds the extension from source against Homebrew's PostgreSQL and
installs it into the PostgreSQL keg, so `CREATE EXTENSION pgokf;` works on a
`brew services`-managed cluster.

## Licensing

pgokf is dual-licensed: AGPL-3.0-only for everyone, with a commercial license
available for uses the AGPL does not permit. See
[LICENSING.md](https://github.com/LogicOcean/pgokf/blob/main/LICENSING.md).

This tap repository contains only packaging metadata.
