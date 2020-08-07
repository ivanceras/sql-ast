# Changelog
All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/), and this project aims to adhere to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

Given that the parser produces a typed AST, any changes to the AST will technically be breaking and thus will result in a `0.(N+1)` version. We document changes that break via addition as "Added".

## [Unreleased]
Nothing here yet! Check https://github.com/andygrove/sqlparser-rs/commits/master for undocumented changes.

## [0.6.0] - Fork from sqlparser
- implement parsing of `IF NOT EXIST` on `CreateTable`

