# Changelog

## v1.3.3 (2020-09-26)

* Bug fixes
  * Graceful error correction of common line continuation faults in Content-Description headers
  * Allow longer attachment filenames to be stored. Cut off at 100 characters.
  * Fix dialyzer warnings

## v1.3.2 (2019-05-24)

* Bug fixes
  * [issue/4](https://github.com/nico-amsterdam/pop3mail/issues/4) Mix compile with pop3mail dependency fails on erlpop.app

## v1.3.1 (2018-11-08)

* Bug fixes
  * [issue/3](https://github.com/nico-amsterdam/pop3mail/issues/3) Lookup headers case-insensitively

## v1.3.0 (2017-11-17)

* Drop support for Elixir 1.2
  * Minimal Elixir 1.3
  * Resolve deprecated warings in Elixir 1.5

## v1.2.1 (2017-06-16)

* Bug fixes
  * Support RFC 2557 Content-Location header.

## v1.2.0 (2017-06-13)

* Bug fixes
  * [issue/2](https://github.com/nico-amsterdam/pop3mail/issues/2) Reduce memory consumption

## v1.1.0 (2017-02-01)

* Bug fixes
  * [issue/1](https://github.com/nico-amsterdam/pop3mail/issues/1) Pass on username unchanged to the mail server. In v1.0.0 it cuts off at the last @ symbol. Example: if username is hendrik.lorentz@gmail.com it logged in with user: hendrik.lorentz
