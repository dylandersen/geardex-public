# GearDex macOS Releases

This repository hosts official GearDex macOS builds and public release notes. Web app changes are delivered at [www.geardex.app](https://www.geardex.app) and do not have downloadable artifacts.

## Channels

| Channel | Purpose | Who should use it |
|---------|---------|-------------------|
| Stable | Regular production builds | Most users |
| Pre-release | Early macOS builds for testing | Users who want to test upcoming desktop changes |

Pre-release builds may include incomplete behavior. Read the release notes before installing them.

Current public notes are tracked in [KNOWN_ISSUES.md](KNOWN_ISSUES.md).

## Version Format

| Example | Meaning |
|---------|---------|
| `v1.2.0` | Stable release |
| `v1.3.0-beta.1` | First beta for `v1.3.0` |
| `v1.3.0-beta.2` | Second beta for `v1.3.0` |

## Choosing a Download

Use the DMG that matches your Mac:

- Apple Silicon: choose the `arm64` DMG
- Intel: choose the standard macOS DMG

Install by opening the DMG and dragging `GearDex.app` into Applications.

## Before Upgrading

- Read the release notes for known issues and behavior changes.
- Check [KNOWN_ISSUES.md](KNOWN_ISSUES.md) for current public notes.
- Back up important local data before testing pre-release builds.
- Confirm you are downloading from [GearDex Releases](https://github.com/dylandersen/geardex-public/releases).
- Keep the previous stable installer available when testing beta builds.

## Reporting Release Feedback

Use the [Pre-release feedback form](https://github.com/dylandersen/geardex-public/issues/new?template=release_feedback.yml) for beta builds.

Include:

- GearDex version
- macOS version
- Apple Silicon or Intel
- What changed compared with the previous build
- Steps, screenshots, or logs if something did not work

For web app problems, use the standard [Bug report form](https://github.com/dylandersen/geardex-public/issues/new?template=bug_report.yml).

## Rollback

If a pre-release build causes problems:

1. Quit GearDex.
2. Reinstall the latest stable build from [Releases](https://github.com/dylandersen/geardex-public/releases).
3. Open an issue with the beta version, stable version, macOS version, and the steps that led to the problem.
