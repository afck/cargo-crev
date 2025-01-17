<p align="center">
  <a href="https://travis-ci.org/dpc/crev">
      <img src="https://img.shields.io/travis/dpc/crev/master.svg?style=flat-square" alt="Travis CI Build Status">
  </a>
  <a href="https://crates.io/crates/cargo-crev">
      <img src="http://meritbadge.herokuapp.com/cargo-crev?style=flat-square" alt="crates.io">
  </a>
  <a href="https://matrix.to/#/!uBhYhtcoNlyEbzfYAW:matrix.org">
    <img src="https://img.shields.io/matrix/crev:matrix.org.svg?server_fqdn=matrix.org&style=flat-square" alt="crev matrix channel">
  </a>
  <a href="https://gitter.im/dpc/crev">
    <img src="https://img.shields.io/gitter/room/dpc/crev.svg?style=flat-square" alt="crev gitter channel">
  </a>
  <br>
</p>

# `cargo-crev` - [Crev](https://github.com/crev-dev/crev) (Code REView system) for Rust/cargo

## Introduction

[Crev](https://github.com/dpc/crev/) is a language and ecosystem agnostic,
distributed Code REView system.

`cargo-crev` is a CLI application implementation/frontend of Crev integrated with `cargo` and targeting
Rust/crates.io ecosystem.

`cargo-crev` is a tool helping Rust users evalute quality and trustworthiness
of dependencies they use.

## Why Rust developers should use `cargo-crev`?

`cargo-crev` can already:

* warn you about untrustworthy crates and security vulnerabilities,
* display useful metrics about your dependencies,
* help you identify dependency-bloat,
* allow you to review most suspicious dependencies and publish your findings,
* use reviews produced by other users,
* increase trustworthiness of your own code,
* build a web of trust of other reputable users to help verify the code you use,

and many other things with many more to come.

## Getting started

Static binaries are availble on [crev's releases](https://github.com/crev-dev/cargo-crev/releases) page.

Follow the [`cargo-crev` - Getting Started Guide](https://github.com/crev-dev/cargo-crev/blob/master/cargo-crev/src/doc/getting_started.md)
(more documentation available on [docs.rs](https://docs.rs/cargo-crev)).

`cargo-crev` is a work in progress, but it should be usable at all times.
Join our [matrix](https://matrix.to/#/!uBhYhtcoNlyEbzfYAW:matrix.org) or [gitter](https://gitter.im/crev-dev/cargo-crev) channel, get help,
report problems and feedback. Thank you!

## Changelog

Changelog can be found here: https://github.com/crev-dev/cargo-crev/blob/master/cargo-crev/CHANGELOG.md
