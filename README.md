# Volume Guard

Volume Guard is a Chrome extension that normalizes and controls the audio of the current browser tab using the Web Audio API.

This is the official public support and documentation repository for Volume Guard. **The proprietary source code of the Volume Guard extension is not published in this repository.**

## About Volume Guard

When you enable Volume Guard, it captures the active tab's audio and processes it locally in your browser. It can make loud audio quieter and quiet audio louder without changing the audio of other tabs.

Captured tab audio is used only for real-time processing. It is not recorded, saved, uploaded, sold, or shared.

## Links

- [Install Volume Guard from the Chrome Web Store](https://chromewebstore.google.com/detail/volume-guard/jphlbijdgpcjanmdjacfhlhidgcbogah)
- [Privacy Policy](./volume_guard_privacy_policy.html)
- [Changelog](./CHANGELOG.md)
- [Security Policy](./SECURITY.md)
- [Issues](https://github.com/NovaDev26316/volume-guard/issues)
- [Releases](https://github.com/NovaDev26316/volume-guard/releases)

## Reporting Bugs and Support

Volume Guard does not automatically send bug reports, usage data, or diagnostics. To report a problem:

1. Use **Copy diagnostics** in the extension popup or support page. The copied template may include the extension version, site, active state, gain, input level, output volume, browser, language, and timestamp.
2. Open the [issue form](https://github.com/NovaDev26316/volume-guard/issues/new/choose), describe the problem, and paste the diagnostics if they are relevant.
3. Review everything you plan to submit and remove private or sensitive information.

GitHub Issues may be public. Do not post personal information, private browsing details, credentials, or other sensitive data.

## Permissions

Volume Guard uses these Chrome extension permissions:

| Permission | Purpose |
| --- | --- |
| `tabCapture` | Captures the audio of the active tab for local processing. |
| `offscreen` | Runs Web Audio processing in an offscreen document. |
| `activeTab` | Identifies the active tab when the user invokes the extension. |
| `storage` | Stores presets, output volume, site exclusions, language settings, and related preferences locally. |

## Privacy

Volume Guard processes active-tab audio locally in the browser. It does not record, save, upload, sell, or share captured audio. Extension preferences may be stored locally in Chrome's extension storage.

See the [Privacy Policy](./volume_guard_privacy_policy.html) for full details and the [`privacy-policies`](./privacy-policies/) directory for version-specific historical policies.

## Release Notes

Public changes are documented in the [Changelog](./CHANGELOG.md). Published packages and release notes may also be available on the [Releases](https://github.com/NovaDev26316/volume-guard/releases) page.

## Feedback

Suggestions and general feedback are welcome. Use the [Feature Request or General Feedback form](https://github.com/NovaDev26316/volume-guard/issues/new/choose) so the discussion remains organized and visible to the community.

## Security

Do not report security vulnerabilities through public GitHub Issues. Follow the private reporting instructions in [SECURITY.md](./SECURITY.md).

## About This Repository

This repository is limited to public-facing material for:

- user support;
- bug reports;
- feature requests and feedback;
- release notes and changelog history;
- privacy and security policies; and
- other public documentation.

It does not contain the proprietary extension source code, and no open-source license is granted or implied.
