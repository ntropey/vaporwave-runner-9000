# 🌴 vaporwave-runner-9000

> *"Chill beats, audio DSP experiments, and continuous release pipelines for retro computing engines."*

A shared multi-target automated build and release scaffold designed to compile and package web-to-native Apple platform projects.

## Architecture

- **Runner Environment:** GitHub Actions macOS 14 (Apple Silicon)
- **Tooling:** Node 22, pnpm 12, Xcode 16.2
- **Codesigning:** Manual Apple Distribution with targeted mobileprovisioning injection
- **Distribution:** Direct automated upload to TestFlight / App Store Connect

## Workflow

Trigger builds on-demand via GitHub Actions `workflow_dispatch` selecting the target project and branch.
