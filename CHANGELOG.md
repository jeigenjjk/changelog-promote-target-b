# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.1.0/).

## [Unreleased]

### Security
- T7: upgrade TLS to 1.3 for all internal service communication

## [20260512.7] chore: T15 seq3 structured logging

### Changed
- T15-seq3: refactor logging to structured JSON format

## [20260512.6] fix: T15 seq2 health check timeout

### Fixed
- T15-seq2: fix request timeout in health check probe

## [20260512.5] feat: T15 seq1 rate limiter

### Added
- T15-seq1: add rate limiter for API gateway

## [20260512.4] fix: T8 slow-merge changelog entry

### Fixed
- T8 slow-merge: fix memory leak in event listener cleanup

## [20260512.3] feat: T8 fast-merge changelog entry

### Added
- T8 fast-merge: new retry logic for webhook delivery

## [20260512.2] feat: T11 cross-repo test

### Added
- Initial project setup for target-b
- T11 cross-repo workflow_call test