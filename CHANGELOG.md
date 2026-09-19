# Changelog

All notable changes to this project will be documented in this file.
The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [1.0.0] - 2026-09-19

### Added
- **Synthetic Test Number Generation**: Generates 10-digit numbers guaranteed to fail the official NHS Modulus 11 validation algorithm.
- **Algorithm Transparency**: Displays the calculated valid check digit alongside the corrupted check digit to prove invalidation logic.
- **Safe Testing Guarantee**: Prevents accidental leakage or test execution using real patient identifiers in staging/QA environments.
- **Live Tool**: Deployed on GitHub Pages at [hazzjc.github.io/InvalidNHSNumberGenerator](https://hazzjc.github.io/InvalidNHSNumberGenerator/).
