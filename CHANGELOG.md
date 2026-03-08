# Changelog

All notable changes to this project will be documented in this file.

The format is inspired by [Keep a Changelog](https://keepachangelog.com/en/1.1.0/), and this project uses semantic version tags.

## [0.1.0] - 2026-03-09

### Added

- Initial public release of `oh-my-tang-dynasty` as an OpenCode plugin package
- 三省六部 orchestration flow with Zhongshu drafting, Menxia review, Shangshu dispatch, and Six Ministries execution
- Operator-facing inspection tools including `tang_status`, `tang_pipeline`, `tang_edicts`, `tang_audit`, `tang_doctor`, `tang_config`, and `tang_reset`
- Runtime-backed execution with deterministic local fallback when OpenCode sessions fail or return unusable structured output
- Deterministic default regression coverage plus an opt-in live clean-env OpenCode regression path
- Minimal release-facing repository metadata, policy files, and CI verification

### Documentation

- Chinese-first default README plus dedicated Chinese and English companion READMEs
- Contribution, security, conduct, and release support documents for the initial public repository
