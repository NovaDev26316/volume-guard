# Changelog

All notable public changes to Volume Guard are documented here.

## Unreleased

### Added

<!-- Document newly added public features here. -->

### Changed

<!-- Document changes to existing public behavior here. -->

### Fixed

<!-- Document public fixes here. -->

## 0.3.2

### Changed

- Reorganized the popup into **Basic**, **Site**, and **Diagnostics** tabs.
- Kept status, current site, current gain, and input level visible near the top of the popup.
- Moved normalization strength, output volume, and Night Mode into the Basic tab.
- Moved current-site preset controls into the Site tab.
- Moved language, membership status, support, diagnostics, update history, and reset controls into the Diagnostics tab.
- Preserved the existing audio-processing logic and stored Night Mode and site-preset data structures.
- Added no new Chrome extension permissions.

## 0.3.1

### Added

- Added an `updatedAt` timestamp to saved site presets.
- Added the saved site-preset count to diagnostics and issue reports.

### Changed

- Limited site presets to the newest 60 entries to protect local storage.
- Made Night Mode gain increases smoother and more conservative.
- Softened limiter release while Night Mode is active.
- Clarified when a saved site preset is active.
- Added no new Chrome extension permissions.

## 0.3.0

### Added

- Added a Night Mode Beta toggle with more conservative audio processing.
- Added controls to save, update, and clear a preset for the current site.
- Stored normalization strength, output volume, and Night Mode state in site presets.
- Added Night Mode and site-preset state to diagnostics and issue-report details.

### Changed

- Used a lower target level and output ceiling with stronger limiting and compression while Night Mode is enabled.
- Added no new Chrome extension permissions.

## 0.2.9

### Added

- Added a Free / Pro state model and a membership-status card to the popup.
- Added plan and feature-state information to issue reports and popup diagnostics.
- Added onboarding guidance distinguishing currently available Free features from prepared feature states.

### Changed

- Kept current-tab normalization, presets, output volume, site exclusions, Korean/English UI, and issue reporting available as Free features.
- Added no new Chrome extension permissions.

## 0.2.8a

### Added

- Added **Copy diagnostics** to the extension popup for user-initiated support sharing.
- Added prefilled issue drafts containing the version, site, active state, gain, input level, browser, language, and timestamp diagnostics.
- Added a public repository link to the support page.

### Changed

- Connected the problem-reporting flow to the public GitHub Issues tracker.
- Expanded help guidance for negative dB values, audio-detection waiting states, unsupported pages, and one-tab processing behavior.
- Kept the Chrome manifest version at `0.2.8` while using the visible maintenance label `0.2.8a`.
- Added no new Chrome extension permissions.
